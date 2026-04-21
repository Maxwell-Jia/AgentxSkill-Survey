// CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目目的

这是一个**科研综述整理**工作目录，不是代码仓库。目标：系统梳理 2026 年 Agent × Skill 方向的论文（重点在 skill 的自动合成 / 自进化 / 沉淀 / 管理 / 评测），并产出一个**分层展示网页**用于组会交流。

用户（中文沟通）是该综述的作者，通常会要求：
- 收集/补充论文信息，写入 `agent-skill-papers-2026.md` 或 `notes/` 精读文件
- 基于已整理内容更新/重构展示网页（HTML）

## 仓库结构（big picture）

- `agent-skill-papers-2026.md` — 论文总目录。已按三大方向（①合成·自进化·沉淀 / ②记忆·失败复用·元学习 / ③生态基建·管理·检索·评测）组织，末尾带汇总表。新增论文需同步更新文内分章节与汇总表两处。
- `notes/<arxiv-id>-<short-name>.md` — 精读笔记，中文。已有模板固定为：元信息表 → Motivation → 核心思路 → 方法（含 Figure 1/2 的 HF 原文链接）→ 实验 → 贡献 / 局限。图片直接用 `https://arxiv.org/html/<id>v1/xN.png` 形式内嵌。新写精读时沿用此结构。
- `docs/` — 所有展示页面与静态资源集中收纳在此目录；根目录保持 md 笔记为核心视角。打开方式：`docs/index.html`。
  - `docs/index.html` — 综述 hub 页，XSkill / Nerfies 风格的单页，含 Hero → Overview → 三大方向论文卡片网格；卡片链到对应 `papers/<id>-<slug>.html`。
  - `docs/papers/<id>-<slug>.html` — 每篇精读论文的独立详情页（XSkill 式单页），通过 `../index.html` 回跳 hub。
  - `docs/static/css/index.css` — 所有页面共用的自定义样式（Nerfies / XSkill 模板的 override 部分）。Bulma / FontAwesome / Academicons / KaTeX 均走 CDN，本地不留副本。
  - `docs/static/images/favicon.svg` — 站点 favicon（暂未在 html 里引用，保留备用）。

## 外部工具：`hf papers` CLI

这是获取论文信息的主要渠道，**优先于 WebFetch**：
- `hf papers search <query>` — 搜索
- `hf papers read <PAPER_ID>` — 拉取 Markdown 全文（含图表占位）
- 元数据、HF 生成的 AI Summary、正文均可从 `hf papers` 命令取得

论文 ID 使用 HF/arXiv 的 `26MM.NNNNN` 格式（2026 年论文）。

## 工作流约定

### 论文处理走 subagent，主上下文不读全文

读取 / 概括论文很占上下文，**必须委派给 subagent**：
- 单篇调研、信息补全 → `Explore` 或 `general-purpose`，模型用 Sonnet 或 Haiku（明确在 Agent 调用里写 `model: "sonnet"` 或 `"haiku"`），只让它回传结构化要点
- 多篇论文可并行时 → **单条消息里发起多个 Agent 调用**，并行跑；用户明确要求"并行"时必须这样做
- 需要保留关键图/表时，告诉 subagent 从 `hf papers read` 输出中抽取 Figure 编号和 arxiv html 图片 URL 一起返回，便于在网页或笔记中内嵌

### 展示网页的设计方向

**参考模板**：`https://xskill-agent.github.io/xskill_page/`（源码：`XSkill-Agent/xskill_page`）。这是著名的 **nerfies / academic-project-page 模板**（Keunhong Park 的 Nerfies 项目页衍生），几乎所有 CV/NLP 顶会论文主页都在用。

**技术栈**（严格沿用模板约定，不要自己发明）：
- **Bulma** CSS 框架（`bulma.min.css`，`is-max-desktop` 容器 ≈ 960px 居中）
- **FontAwesome + Academicons**（arXiv / GitHub 图标）
- 字体：`Google Sans`（标题 / 作者）+ `Noto Sans`（正文）+ `Castoro`（装饰）
- jQuery（可选，模板自带）

**视觉语言**：
- **居中单列**布局，段落两端对齐（`content has-text-justified`）
- **交替段落底色**制造节奏：白 / `#eef1f6` / 白 / `#eef1f6` …（给 `section` 直接加 `style="background-color:#eef1f6"`）
- **大标题 + small-caps 渐变品牌名**：比如 XSkill 的品牌名用 `background: linear-gradient(90deg,#F97316,#22C55E); -webkit-background-clip:text; -webkit-text-fill-color:transparent; font-variant:small-caps;`。每个项目/论文可以配一套自己的渐变色。
- **三色 pill 按钮**（arXiv 红 `#b31b1b` · GitHub 黑 `#24292e` · HuggingFace 橙 `#ff9d00`），`.button.is-rounded`，放在 hero 底部居中
- **作者行**：`author-block`（inline-block）+ 上标数字；下面一行机构 + 再下面一行 `*Equal contribution`
- **章节标题**：`h2.title.is-3`，居中
- **图**：`analysis-figure-wrap` — 圆角 8~12px + 淡边框 `#dde3ea` + 轻阴影 `0 2px 12px rgba(0,0,0,0.06)`，配 `figure-caption`（italic、`#546e7a`、小号）
- **表**：结果表头深色 `#37474f` 白字；"our method" 行淡绿高亮 `#e8f5e9`
- **内容卡片**（`analysis-card`）：白底 + `#e4e8ee` 细边 + 12px 圆角 + 轻阴影，用 Bulma columns 做网格

**一篇论文详情页的内容节奏**（沿用 xskill 页的结构顺序）：Hero → Teaser 图 → Abstract → Framework Overview（含大图） → Results 表 → Analysis（小卡片网格）→ BibTeX/引用 → footer。本地调整：可以用 Key Insight 框替代 BibTeX。

**本仓库站点的层级结构**（全部收纳在 `docs/` 下，根目录保留 md 笔记为核心）：
- `docs/index.html` 是 **综述 hub 页**，把它当作一个"元论文页"来做——hero 区用综述名而不是某篇论文名，"Results" 段落替换为按方向分类的论文卡片网格。
- `docs/papers/<id>-<slug>.html` 每篇精读论文一个文件，各自是完整的 xskill 式单页；通过 `../static/css/index.css` 与 hub 共用样式，`../index.html` 回跳。
- 共享 CSS 放 `docs/static/css/index.css`（Bulma / FontAwesome / Academicons / KaTeX 全部从 CDN 加载，自定义 CSS 只写 Nerfies 模板的 override 部分）。
- **XSkill 论文本身**（`2603.12056`）不再单独做一页 html，其内容统一以精读笔记 `notes/2603.12056-XSkill.md` 形式沉淀；hub 页只保留一张卡片。

**不要做**的事：
- 不要用 Tailwind / 自造设计系统——既然参考模板已经稳定且业内通用，直接沿用。
- 不要在项目根目录新建零散 html；所有 web 产物都进 `docs/`。

### 语言

所有笔记、网页文案、与用户的沟通默认**中文**。论文标题、作者、术语保留英文原文。
