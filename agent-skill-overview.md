# Agent × Skill 相关论文 (2026-02 以来)

**主题**:skill 的自动合成、更新、沉淀,用以提升 agent 性能。
**来源**:Hugging Face Papers (`hf papers search`),摘要为 HF 官方 AI Summary。
**采集日期**:2026-04-20

---

## 一、核心方向:skill 自动合成 · 自进化 · 沉淀

### [2602.01983](https://huggingface.co/papers/2602.01983) — Evolving from Tool User to Creator via Training-Free Experience Reuse in Multimodal Reasoning
- **日期**:2026-02-03 · **👍** 2 · **机构**:LiAuto Foundation Model
- **AI Summary**:A training-free framework enables language model agents to automatically create and optimize tools during inference, improving their reasoning capabilities through self-evolution and memory consolidation.

### [2602.03279](https://huggingface.co/papers/2602.03279) — Agentic Proposing: Enhancing Large Language Model Reasoning via Compositional Skill Synthesis
- **日期**:2026-02-03 · **👍** 0
- **AI Summary**:Agentic Proposing framework uses specialized agents with Multi-Granularity Policy Optimization to synthesize high-quality, verifiable training data for complex reasoning tasks, achieving state-of-the-art performance with minimal human annotation.

### [2602.08234](https://huggingface.co/papers/2602.08234) — SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning
- **日期**:2026-02-11 · **👍** 74 · **机构**:University of North Carolina at Chapel Hill · **Code**:[aiming-lab/SkillRL](https://github.com/aiming-lab/SkillRL)
- **AI Summary**:SkillRL enables LLM agents to improve through hierarchical skill discovery and recursive policy evolution, achieving superior performance on complex tasks while reducing computational overhead.

### [2602.21320](https://huggingface.co/papers/2602.21320) — Tool-R0: Self-Evolving LLM Agents for Tool-Learning from Zero Data
- **日期**:2026-03-03 · **👍** 12 · **机构**:University of Illinois at Urbana-Champaign · **Code**:[emrecanacikgoz/Tool-R0](https://github.com/emrecanacikgoz/Tool-R0)
- **AI Summary**:Tool-R0 framework enables training general-purpose tool-calling agents through self-play reinforcement learning without initial datasets, achieving significant performance improvements over base models and supervised baselines.

### [2603.01145](https://huggingface.co/papers/2603.01145) — AutoSkill: Experience-Driven Lifelong Learning via Skill Self-Evolution
- **日期**:2026-03-01 · **👍** 0
- **AI Summary**:AutoSkill is a lifelong learning framework that enables LLM agents to automatically derive, maintain, and reuse skills from user interactions without retraining the underlying model.

### [2603.02766](https://huggingface.co/papers/2603.02766) — EvoSkill: Automated Skill Discovery for Multi-Agent Systems
- **日期**:2026-03-03 · **👍** 1
- **AI Summary**:EvoSkill is a self-evolving framework that automatically discovers and refines agent skills through iterative failure analysis, improving performance on grounded reasoning and search-augmented QA benchmarks while enabling zero-shot transfer between tasks.

### [2603.04448](https://huggingface.co/papers/2603.04448) — SkillNet: Create, Evaluate, and Connect AI Skills
- **日期**:2026-02-26 · **👍** 93 · **机构**:Zhejiang University + Alibaba + Tencent + UCLA · **Code**:[zjunlp/SkillNet](https://github.com/zjunlp/SkillNet)
- **AI Summary**:SkillNet provides an open-source Python toolkit with 200K+ SKILL.md artifacts; skills are organized as structured folders with a central SKILL.md file, accessed via a Discovery → Activation → Execution protocol.

### [2603.05578](https://huggingface.co/papers/2603.05578) — Tool-Genesis: A Task-Driven Tool Creation Benchmark for Self-Evolving Language Agent
- **日期**:2026-03-05 · **👍** 0
- **AI Summary**:Tool-Genesis presents a diagnostic benchmark for evaluating language agents' ability to autonomously create and utilize tools from abstract requirements, revealing current limitations in one-shot tool synthesis and execution.

### [2603.12056](https://huggingface.co/papers/2603.12056) — XSkill: Continual Learning from Experience and Skills in Multimodal Agents
- **日期**:2026-03-12 · **👍** 33
- **AI Summary**:XSkill is a dual-stream framework for multimodal agents that continually accumulates two complementary forms of reusable knowledge — experiences (action-level guidance for tool selection) and skills (task-level guidance for planning) — via visually grounded summarization and cross-rollout critique, with retrieval and usage history forming a closed continual-learning loop; consistently outperforms tool-only and learning-based baselines across five benchmarks and four backbone models without parameter updates.

### [2603.14805](https://huggingface.co/papers/2603.14805) — Knowledge Activation: AI Skills as the Institutional Knowledge Primitive for Agentic Software Development
- **日期**:2026-03-16 · **👍** 0
- **AI Summary**:Specializes the Anthropic AI Skills open standard into Atomic Knowledge Units (AKUs) — a seven-component schema (intent, procedure, tools, metadata, governance, continuations, validators) for institutional knowledge delivery in agentic software development.

### [2603.16060](https://huggingface.co/papers/2603.16060) — ARISE: Agent Reasoning with Intrinsic Skill Evolution in Hierarchical Reinforcement Learning
- **日期**:2026-03-18 · **👍** 3 · **机构**:George Washington University · **Code**:[Skylanding/ARISE](https://github.com/Skylanding/ARISE)
- **AI Summary**:A hierarchical reinforcement learning framework named ARISE employs a skill management system to improve mathematical reasoning in language models through reusable strategies and structured skill libraries.

### [2603.18000](https://huggingface.co/papers/2603.18000) — AgentFactory: A Self-Evolving Framework Through Executable Subagent Accumulation and Reuse
- **日期**:2026-03-18 · **👍** 0
- **AI Summary**:AgentFactory enables LLM-based agents to evolve through executable subagent code preservation and refinement, allowing continuous capability accumulation without manual intervention.

### [2603.18743](https://huggingface.co/papers/2603.18743) — Memento-Skills: Let Agents Design Agents
- **日期**:2026-03-20 · **👍** 57 · **机构**:University College London · **Code**:[Memento-Teams/Memento-Skills](https://github.com/Memento-Teams/Memento-Skills)
- **AI Summary**:A generalist language model agent system autonomously designs and improves task-specific agents through memory-based reinforcement learning with stateful prompts and skill libraries.

### [2603.24639](https://huggingface.co/papers/2603.24639) — Experiential Reflective Learning for Self-Improving LLM Agents
- **日期**:2026-03-25 · **👍** 3 · **机构**:Illuin Technology
- **AI Summary**:Experiential Reflective Learning framework enables autonomous agents to adapt rapidly to new environments by learning from past experiences and transferring actionable insights across tasks.

### [2603.25158](https://huggingface.co/papers/2603.25158) — Trace2Skill: Distill Trajectory-Local Lessons into Transferable Agent Skills
- **日期**:2026-03-30 · **👍** 50
- **AI Summary**:Trace2Skill enables scalable skill generation for LLM agents by analyzing diverse execution traces in parallel and consolidating them into transferable, declarative skills without parameter updates or external modules.

### [2603.27850](https://huggingface.co/papers/2603.27850) — EffiSkill: Agent Skill Based Automated Code Efficiency Optimization
- **日期**:2026-03-29 · **👍** 1
- **AI Summary**:Agent skill-based code efficiency optimization; mines Operator Skills and Meta Skills offline, stored as skill cards with YAML-like metadata (skill_id, type, language, description, triggers) forming a pluggable optimization toolkit.

### [2604.01687](https://huggingface.co/papers/2604.01687) — EvoSkills: Self-Evolving Agent Skills via Co-Evolutionary Verification
- **日期**:2026-04-02 · **👍** 6 · **机构**:University of Illinois Chicago + MBZUAI + McGill + Columbia
- **AI Summary**:Self-evolving agent skills via co-evolutionary verification; a Skill Generator and a Surrogate Verifier co-evolve to automatically produce executable multi-file skill bundles (SKILL.md + scripts + resources), achieving 71.1% pass rate on SkillsBench (+40.5pp over no-skill baseline). *注：与 2603.02766 EvoSkill(单数) 是不同工作。*

### [2604.02268](https://huggingface.co/papers/2604.02268) — SKILL0: In-Context Agentic Reinforcement Learning for Skill Internalization
- **日期**:2026-04-03 · **👍** 94 · **Code**:[ZJU-REAL/SkillZero](https://github.com/ZJU-REAL/SkillZero)
- **AI Summary**:SKILL0 enables LLM agents to internalize skills during training, allowing zero-shot autonomous behavior through a dynamic curriculum that reduces contextual overhead while improving task performance.

### [2604.03964](https://huggingface.co/papers/2604.03964) — SKILLFOUNDRY: Building Self-Evolving Agent Skill Libraries from Heterogeneous Scientific Resources
- **日期**:2026-04-05 · **👍** 0
- **AI Summary**:SkillFoundry automatically converts fragmented scientific knowledge into validated agent skills through a self-evolving framework that mines resources, extracts operational contracts, and builds reusable skill libraries for improved scientific agent performance.

### [2604.04804](https://huggingface.co/papers/2604.04804) — SkillX: Automatically Constructing Skill Knowledge Bases for Agents
- **日期**:2026-04-07 · **👍** 32 · **机构**:Zhejiang University · **Code**:[zjunlp/SkillX](https://github.com/zjunlp/SkillX)
- **AI Summary**:SkillX is an automated framework that creates reusable skill libraries for LLM agents through hierarchical skill design, iterative refinement, and exploratory expansion to improve generalization and efficiency across different environments.

### [2604.08377](https://huggingface.co/papers/2604.08377) — SkillClaw: Let Skills Evolve Collectively with Agentic Evolver
- **日期**:2026-04-09 · **👍** 282 · **机构**:AMAP-ML (Alibaba) · **Code**:[AMAP-ML/SkillClaw](https://github.com/AMAP-ML/SkillClaw)
- **AI Summary**:Autonomous evolver for OpenClaw agents that continuously aggregates cross-user interaction trajectories and updates a shared skill set; evaluated on WildClawBench with significant gains on Qwen3-Max.

---

## 二、相关:自进化记忆 · 失败经验复用 · 元学习

### [2602.02474](https://huggingface.co/papers/2602.02474) — MemSkill: Learning and Evolving Memory Skills for Self-Evolving Agents
- **日期**:2026-02-02 · **👍** 63 · **机构**:Nanyang Technological University · **Code**:[ViktorAxelsen/MemSkill](https://github.com/ViktorAxelsen/MemSkill)
- **AI Summary**:MemSkill equips self-evolving agents with memory skills (description + content specification), selected by a controller, executed by an executor, and continuously evolved by a designer — a shared skill bank inspired by the design philosophy of agent skills.

### [2602.05832](https://huggingface.co/papers/2602.05832) — UI-Mem: Self-Evolving Experience Memory for Online Reinforcement Learning in Mobile GUI Agents
- **日期**:2026-02-05 · **👍** 0
- **AI Summary**:UI-Mem framework enhances GUI online reinforcement learning through hierarchical experience memory and stratified sampling to improve credit assignment and experience transfer in long-horizon tasks.

### [2603.09716](https://huggingface.co/papers/2603.09716) — AutoAgent: Evolving Cognition and Elastic Memory Orchestration for Adaptive Agents
- **日期**:2026-03-10 · **👍** 0
- **AI Summary**:AutoAgent is a self-evolving multi-agent framework that integrates dynamic cognition, real-time decision-making, and adaptive memory management to enable autonomous agents to learn from experience while making context-aware decisions in dynamic environments.

### [2603.17187](https://huggingface.co/papers/2603.17187) — MetaClaw: Just Talk — An Agent That Meta-Learns and Evolves in the Wild
- **日期**:2026-03-19 · **👍** 138 · **机构**:University of North Carolina at Chapel Hill · **Code**:[aiming-lab/MetaClaw](https://github.com/aiming-lab/MetaClaw)
- **AI Summary**:A continual meta-learning framework for large language model agents that jointly evolves policies and reusable behavioral skills while minimizing downtime through opportunistic updates and skill-driven adaptation.

### [2603.19461](https://huggingface.co/papers/2603.19461) — Hyperagents
- **日期**:2026-03-23 · **👍** 50 · **Code**:[facebookresearch/Hyperagents](https://github.com/facebookresearch/Hyperagents)
- **AI Summary**:Hyperagents represent a self-referential framework that integrates task and meta-agents into a single editable program, enabling metacognitive self-modification and open-ended improvement across diverse computational domains.

### [2603.24533](https://huggingface.co/papers/2603.24533) — UI-Voyager: A Self-Evolving GUI Agent Learning via Failed Experience
- **日期**:2026-03-26 · **👍** 47 · **机构**:Tencent · **Code**:[ui-voyager/UI-Voyager](https://github.com/ui-voyager/UI-Voyager)
- **AI Summary**:A two-stage self-evolving mobile GUI agent named UI-Voyager is proposed, featuring rejection fine-tuning and group relative self-distillation to improve efficiency and performance in GUI automation tasks.

---

## 三、生态基建:skill 分析 · 管理 · 检索 · 评测 · 安全

### [2602.08004](https://huggingface.co/papers/2602.08004) — Agent Skills: A Data-Driven Analysis of Claude Skills for Extending Large Language Model Functionality
- **日期**:2026-02-10 · **👍** 5
- **AI Summary**:*(HF AI summary 暂缺)* — 论文对 Claude Skills 生态进行数据驱动分析,给出 skill 作为可复用程序化模块在触发条件、过程逻辑、工具交互方面的结构特征。

### [2602.12430](https://huggingface.co/papers/2602.12430) — Agent Skills for Large Language Models: Architecture, Acquisition, Security, and the Path Forward
- **日期**:2026-02-12 · **👍** 1
- **AI Summary**:Modern language models are evolving toward modular agent architectures that dynamically load skills on demand, enabling flexible deployment and security governance through standardized protocols and lifecycle management frameworks.

### [2602.12670](https://huggingface.co/papers/2602.12670) — SkillsBench: Benchmarking How Well Agent Skills Work Across Diverse Tasks
- **日期**:2026-02-18 · **👍** 60 · **机构**:BenchFlow · **Code**:[benchflow-ai/skillsbench](https://github.com/benchflow-ai/skillsbench)
- **AI Summary**:SkillsBench evaluates agent skills across 86 tasks and finds that curated skills improve performance significantly but inconsistently, while self-generated skills offer no benefit, indicating that models struggle to create useful procedural knowledge despite benefiting from curated versions.

### [2602.20156](https://huggingface.co/papers/2602.20156) — Skill-Inject: Measuring Agent Vulnerability to Skill File Attacks
- **日期**:2026-02-23 · **👍** 0 · **机构**:Max Planck Institute for Intelligent Systems
- **AI Summary**:Identifies skill-based prompt injection as a significant threat to agent skill files, demonstrating attacks against real Claude Code / Gemini CLI / Codex CLI SKILL.md artifacts and quantifying the attack surface of the emerging skill ecosystem.

### [2602.20867](https://huggingface.co/papers/2602.20867) — SoK: Agentic Skills — Beyond Tool Use in LLM Agents
- **日期**:2026-02-24 · **👍** 1
- **AI Summary**:Systematization of Knowledge paper on agentic skills beyond tool use — formalizing skill as S=(C,π,T,R) and organizing seven design patterns from metadata-driven progressive disclosure to self-evolving libraries and marketplace distribution.

### [2603.00195](https://huggingface.co/papers/2603.00195) — Formal Analysis and Supply Chain Security for Agentic AI Skills
- **日期**:2026-02-27 · **👍** 0
- **AI Summary**:Formal analysis of the agentic AI skill supply chain (OpenClaw 228K stars, Anthropic Agent Skills 75.6K stars); introduces SkillFortifyBench with 540 real-world skill artifacts and a five-stage skill lifecycle (authorship / registry publication / installation / execution / state persistence).

### [2603.02176](https://huggingface.co/papers/2603.02176) — Organizing, Orchestrating, and Benchmarking Agent Skills at Ecosystem Scale
- **日期**:2026-03-02 · **👍** 2 · **Code**:[ynulihao/AgentSkillOS](https://github.com/ynulihao/AgentSkillOS)
- **AI Summary**:AgentSkillOS presents a framework for managing and scaling AI agent skills through hierarchical organization and directed acyclic graph-based orchestration, demonstrating superior performance over flat invocation methods.

### [2603.15401](https://huggingface.co/papers/2603.15401) — SWE-Skills-Bench: Do Agent Skills Actually Help in Real-World Software Engineering?
- **日期**:2026-03-16 · **👍** 19 · **机构**:MBZUAI + Nanjing University · **Code**:[GeniusHTX/SWE-Skills-Bench](https://github.com/GeniusHTX/SWE-Skills-Bench)
- **AI Summary**:Benchmarks whether structured procedural knowledge packages (agent skills) actually help in real-world software engineering, pairing 49 public SWE skills in Anthropic format with real GitHub repositories.

### [2603.21019](https://huggingface.co/papers/2603.21019) — SkillProbe: Security Auditing for Emerging Agent Skill Marketplaces via Multi-Agent Collaboration
- **日期**:2026-03-22 · **👍** 0 · **机构**:Shanghai Jiao Tong University
- **AI Summary**:Security auditing framework for agent skill marketplaces; evaluates 2500 real-world skills from ClawHub using a Skills-for-Skills design paradigm that encapsulates auditing processes into standardized skill modules.

### [2603.22455](https://huggingface.co/papers/2603.22455) — SkillRouter: Retrieve-and-Rerank Skill Selection for LLM Agents at Scale
- **日期**:2026-03-23 · **👍** 2
- **AI Summary**:Skill routing in large language model agent ecosystems requires retrieving relevant skills from vast repositories, with implementation details proving more important than metadata for accurate selection.

### [2604.04323](https://huggingface.co/papers/2604.04323) — How Well Do Agentic Skills Work in the Wild: Benchmarking LLM Skill Usage in Realistic Settings
- **日期**:2026-04-08 · **👍** 40 · **机构**:Shiyu's Lab · **Code**:[UCSB-NLP-Chang/Skill-Usage](https://github.com/UCSB-NLP-Chang/Skill-Usage)
- **AI Summary**:Research demonstrates that skill utilization in LLM-based agents degrades significantly under realistic conditions where skills must be retrieved and refined rather than handcrafted, though targeted refinement strategies can partially restore performance.

### [2604.05333](https://huggingface.co/papers/2604.05333) — Graph of Skills: Dependency-Aware Structural Retrieval for Massive Agent Skills
- **日期**:2026-04-10 · **👍** 22 · **机构**:University of Pennsylvania · **Code**:[davidliuk/graph-of-skills](https://github.com/davidliuk/graph-of-skills)
- **AI Summary**:Graph of Skills (GoS) enables efficient inference in large skill libraries by constructing executable skill graphs and retrieving dependency-aware bundles through hybrid retrieval methods, significantly improving reward performance while reducing token usage.

### [2604.08224](https://huggingface.co/papers/2604.08224) — Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering
- **日期**:2026-04-09 · **👍** 50 · **机构**:Shanghai Jiao Tong University + CMU + OPPO
- **AI Summary**:Unified review of externalization in LLM agents across memory, skills, protocols and harness engineering; covers Anthropic-format skill specification, discovery, progressive disclosure, execution binding and composition as Stage 3: Skill as Packaged Expertise.

### [2604.14228](https://huggingface.co/papers/2604.14228) — Dive into Claude Code: The Design Space of Today's and Future AI Agent Systems
- **日期**:2026-04-14 · **👍** 22 · **机构**:VILA Lab · **Code**:[VILA-Lab/Dive-into-Claude-Code](https://github.com/VILA-Lab/Dive-into-Claude-Code)
- **AI Summary**:Systematic reverse-engineering of Claude Code's TypeScript sources, mapping its four extensibility mechanisms — MCP, plugins, skills, hooks — to characterize the design space of current and future AI agent systems.

### [2604.14572](https://huggingface.co/papers/2604.14572) — Don't Retrieve, Navigate: Distilling Enterprise Knowledge into Navigable Agent Skills for QA and RAG
- **日期**:2026-04-16 · **👍** 6 · **Code**:[dukesun99/Corpus2Skill](https://github.com/dukesun99/Corpus2Skill)
- **AI Summary**:Distills a document corpus into a hierarchical tree of navigable skill files offline, letting an LLM agent navigate the tree at serve time rather than retrieve chunks — skill files as a RAG alternative for QA over enterprise knowledge.

### [2604.17308](https://huggingface.co/papers/2604.17308) — SkillFlow: Benchmarking Lifelong Skill Discovery and Evolution for Autonomous Agents
- **日期**:2026-04-19 · **👍** 16 · **机构**:USTC + University of Toronto + University of Sydney · **Code**:[ZhangZi-a/SkillFlow](https://github.com/ZhangZi-a/SkillFlow)
- **AI Summary**:Benchmark for lifelong skill discovery and evolution; agents begin with no skills, externalize lessons through trajectory- and rubric-driven skill patches, and carry the updated library forward across task families (Claude Opus 4.6 gains +8.43 points).

---

## 汇总表

| ID | 标题 | 日期 | 👍 | 方向 |
|---|---|---|---|---|
| [2602.01983](https://huggingface.co/papers/2602.01983) | Tool User → Creator (Training-Free Experience Reuse) | 2026-02-03 | 2 | 合成 |
| [2602.02474](https://huggingface.co/papers/2602.02474) | MemSkill (Memory Skills) | 2026-02-02 | 63 | 记忆 |
| [2602.03279](https://huggingface.co/papers/2602.03279) | Agentic Proposing (Compositional Skill Synthesis) | 2026-02-03 | 0 | 合成 |
| [2602.05832](https://huggingface.co/papers/2602.05832) | UI-Mem (Self-Evolving Experience Memory) | 2026-02-05 | 0 | 记忆 |
| [2602.08004](https://huggingface.co/papers/2602.08004) | Data-Driven Analysis of Claude Skills | 2026-02-10 | 5 | 分析 |
| [2602.08234](https://huggingface.co/papers/2602.08234) | SkillRL (Recursive Skill-Augmented RL) | 2026-02-11 | 74 | 自进化 |
| [2602.12430](https://huggingface.co/papers/2602.12430) | Agent Skills 综述:架构/获取/安全 | 2026-02-12 | 1 | 综述 |
| [2602.12670](https://huggingface.co/papers/2602.12670) | SkillsBench | 2026-02-18 | 60 | 评测 |
| [2602.20156](https://huggingface.co/papers/2602.20156) | Skill-Inject (SKILL.md 攻击面) | 2026-02-23 | 0 | 安全 |
| [2602.20867](https://huggingface.co/papers/2602.20867) | SoK: Agentic Skills (七种设计模式) | 2026-02-24 | 1 | 综述 |
| [2602.21320](https://huggingface.co/papers/2602.21320) | Tool-R0 (Zero-Data Self-Evolving Tool Learning) | 2026-03-03 | 12 | 自进化 |
| [2603.00195](https://huggingface.co/papers/2603.00195) | Formal Analysis & Supply Chain Security | 2026-02-27 | 0 | 安全 |
| [2603.01145](https://huggingface.co/papers/2603.01145) | AutoSkill (Lifelong Skill Self-Evolution) | 2026-03-01 | 0 | 沉淀 |
| [2603.02176](https://huggingface.co/papers/2603.02176) | AgentSkillOS (Ecosystem-Scale Orchestration) | 2026-03-02 | 2 | 管理 |
| [2603.02766](https://huggingface.co/papers/2603.02766) | EvoSkill (单数, Automated Skill Discovery) | 2026-03-03 | 1 | 合成 |
| [2603.04448](https://huggingface.co/papers/2603.04448) | SkillNet (200K+ SKILL.md 工具集) | 2026-02-26 | 93 | 管理 |
| [2603.05578](https://huggingface.co/papers/2603.05578) | Tool-Genesis (Tool Creation Benchmark) | 2026-03-05 | 0 | 评测 |
| [2603.09716](https://huggingface.co/papers/2603.09716) | AutoAgent (Cognition + Elastic Memory) | 2026-03-10 | 0 | 记忆 |
| [2603.12056](https://huggingface.co/papers/2603.12056) | XSkill (Experience + Skill Dual-Stream Continual Learning) | 2026-03-12 | 33 | 沉淀 |
| [2603.14805](https://huggingface.co/papers/2603.14805) | Knowledge Activation (AKU 七组件 schema) | 2026-03-16 | 0 | 沉淀 |
| [2603.15401](https://huggingface.co/papers/2603.15401) | SWE-Skills-Bench (真实 SWE 场景评测) | 2026-03-16 | 19 | 评测 |
| [2603.16060](https://huggingface.co/papers/2603.16060) | ARISE (Intrinsic Skill Evolution) | 2026-03-18 | 3 | 自进化 |
| [2603.17187](https://huggingface.co/papers/2603.17187) | MetaClaw (Meta-Learn in the Wild) | 2026-03-19 | 138 | 元学习 |
| [2603.18000](https://huggingface.co/papers/2603.18000) | AgentFactory (Subagent Accumulation) | 2026-03-18 | 0 | 沉淀 |
| [2603.18743](https://huggingface.co/papers/2603.18743) | Memento-Skills (Agents Design Agents) | 2026-03-20 | 57 | 自进化 |
| [2603.19461](https://huggingface.co/papers/2603.19461) | Hyperagents (Self-Referential Framework) | 2026-03-23 | 50 | 元学习 |
| [2603.21019](https://huggingface.co/papers/2603.21019) | SkillProbe (ClawHub 2500 skill 审计) | 2026-03-22 | 0 | 安全 |
| [2603.22455](https://huggingface.co/papers/2603.22455) | SkillRouter (Retrieve-and-Rerank) | 2026-03-23 | 2 | 检索 |
| [2603.24533](https://huggingface.co/papers/2603.24533) | UI-Voyager (Self-Evolving GUI via Failure) | 2026-03-26 | 47 | 自进化 |
| [2603.24639](https://huggingface.co/papers/2603.24639) | Experiential Reflective Learning | 2026-03-25 | 3 | 沉淀 |
| [2603.25158](https://huggingface.co/papers/2603.25158) | Trace2Skill (Trajectory → Transferable Skill) | 2026-03-30 | 50 | 合成 |
| [2603.27850](https://huggingface.co/papers/2603.27850) | EffiSkill (Code Efficiency Skill Cards) | 2026-03-29 | 1 | 合成 |
| [2604.01687](https://huggingface.co/papers/2604.01687) | EvoSkills (复数, Co-Evolutionary Verification) | 2026-04-02 | 6 | 自进化 |
| [2604.02268](https://huggingface.co/papers/2604.02268) | SKILL0 (In-Context Skill Internalization) | 2026-04-03 | 94 | 沉淀 |
| [2604.03964](https://huggingface.co/papers/2604.03964) | SKILLFOUNDRY (Self-Evolving Scientific Skill Lib) | 2026-04-05 | 0 | 沉淀 |
| [2604.04323](https://huggingface.co/papers/2604.04323) | LLM Skill Usage in the Wild | 2026-04-08 | 40 | 评测 |
| [2604.04804](https://huggingface.co/papers/2604.04804) | SkillX (Auto Skill KB Construction) | 2026-04-07 | 32 | 沉淀 |
| [2604.05333](https://huggingface.co/papers/2604.05333) | Graph of Skills (Dependency-Aware Retrieval) | 2026-04-10 | 22 | 检索 |
| [2604.08224](https://huggingface.co/papers/2604.08224) | Externalization 综述 (Memory/Skills/Protocols/Harness) | 2026-04-09 | 50 | 综述 |
| [2604.08377](https://huggingface.co/papers/2604.08377) | SkillClaw (Collective Skill Evolution) | 2026-04-09 | 282 | 自进化 |
| [2604.14228](https://huggingface.co/papers/2604.14228) | Dive into Claude Code (MCP/plugins/skills/hooks) | 2026-04-14 | 22 | 分析 |
| [2604.14572](https://huggingface.co/papers/2604.14572) | Corpus2Skill (Navigate, Don't Retrieve) | 2026-04-16 | 6 | 检索 |
| [2604.17308](https://huggingface.co/papers/2604.17308) | SkillFlow (Lifelong Skill Discovery Benchmark) | 2026-04-19 | 16 | 评测 |

---

*获取单篇 Markdown 全文*:`hf papers read <PAPER_ID>`
