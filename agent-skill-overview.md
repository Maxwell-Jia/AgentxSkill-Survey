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

### [2603.05578](https://huggingface.co/papers/2603.05578) — Tool-Genesis: A Task-Driven Tool Creation Benchmark for Self-Evolving Language Agent
- **日期**:2026-03-05 · **👍** 0
- **AI Summary**:Tool-Genesis presents a diagnostic benchmark for evaluating language agents' ability to autonomously create and utilize tools from abstract requirements, revealing current limitations in one-shot tool synthesis and execution.

### [2603.12056](https://huggingface.co/papers/2603.12056) — XSkill: Continual Learning from Experience and Skills in Multimodal Agents
- **日期**:2026-03-12 · **👍** 33
- **AI Summary**:XSkill is a dual-stream framework for multimodal agents that continually accumulates two complementary forms of reusable knowledge — experiences (action-level guidance for tool selection) and skills (task-level guidance for planning) — via visually grounded summarization and cross-rollout critique, with retrieval and usage history forming a closed continual-learning loop; consistently outperforms tool-only and learning-based baselines across five benchmarks and four backbone models without parameter updates.

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

### [2604.02268](https://huggingface.co/papers/2604.02268) — SKILL0: In-Context Agentic Reinforcement Learning for Skill Internalization
- **日期**:2026-04-03 · **👍** 94 · **Code**:[ZJU-REAL/SkillZero](https://github.com/ZJU-REAL/SkillZero)
- **AI Summary**:SKILL0 enables LLM agents to internalize skills during training, allowing zero-shot autonomous behavior through a dynamic curriculum that reduces contextual overhead while improving task performance.

### [2604.03964](https://huggingface.co/papers/2604.03964) — SKILLFOUNDRY: Building Self-Evolving Agent Skill Libraries from Heterogeneous Scientific Resources
- **日期**:2026-04-05 · **👍** 0
- **AI Summary**:SkillFoundry automatically converts fragmented scientific knowledge into validated agent skills through a self-evolving framework that mines resources, extracts operational contracts, and builds reusable skill libraries for improved scientific agent performance.

### [2604.04804](https://huggingface.co/papers/2604.04804) — SkillX: Automatically Constructing Skill Knowledge Bases for Agents
- **日期**:2026-04-07 · **👍** 32 · **机构**:Zhejiang University · **Code**:[zjunlp/SkillX](https://github.com/zjunlp/SkillX)
- **AI Summary**:SkillX is an automated framework that creates reusable skill libraries for LLM agents through hierarchical skill design, iterative refinement, and exploratory expansion to improve generalization and efficiency across different environments.

---

## 二、相关:自进化记忆 · 失败经验复用 · 元学习

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

## 三、生态基建:skill 分析 · 管理 · 检索 · 评测

### [2602.08004](https://huggingface.co/papers/2602.08004) — Agent Skills: A Data-Driven Analysis of Claude Skills for Extending Large Language Model Functionality
- **日期**:2026-02-10 · **👍** 5
- **AI Summary**:*(HF AI summary 暂缺)* — 论文对 Claude Skills 生态进行数据驱动分析,给出 skill 作为可复用程序化模块在触发条件、过程逻辑、工具交互方面的结构特征。

### [2602.12430](https://huggingface.co/papers/2602.12430) — Agent Skills for Large Language Models: Architecture, Acquisition, Security, and the Path Forward
- **日期**:2026-02-12 · **👍** 1
- **AI Summary**:Modern language models are evolving toward modular agent architectures that dynamically load skills on demand, enabling flexible deployment and security governance through standardized protocols and lifecycle management frameworks.

### [2602.12670](https://huggingface.co/papers/2602.12670) — SkillsBench: Benchmarking How Well Agent Skills Work Across Diverse Tasks
- **日期**:2026-02-18 · **👍** 60 · **机构**:BenchFlow · **Code**:[benchflow-ai/skillsbench](https://github.com/benchflow-ai/skillsbench)
- **AI Summary**:SkillsBench evaluates agent skills across 86 tasks and finds that curated skills improve performance significantly but inconsistently, while self-generated skills offer no benefit, indicating that models struggle to create useful procedural knowledge despite benefiting from curated versions.

### [2603.02176](https://huggingface.co/papers/2603.02176) — Organizing, Orchestrating, and Benchmarking Agent Skills at Ecosystem Scale
- **日期**:2026-03-02 · **👍** 2 · **Code**:[ynulihao/AgentSkillOS](https://github.com/ynulihao/AgentSkillOS)
- **AI Summary**:AgentSkillOS presents a framework for managing and scaling AI agent skills through hierarchical organization and directed acyclic graph-based orchestration, demonstrating superior performance over flat invocation methods.

### [2603.22455](https://huggingface.co/papers/2603.22455) — SkillRouter: Retrieve-and-Rerank Skill Selection for LLM Agents at Scale
- **日期**:2026-03-23 · **👍** 2
- **AI Summary**:Skill routing in large language model agent ecosystems requires retrieving relevant skills from vast repositories, with implementation details proving more important than metadata for accurate selection.

### [2604.04323](https://huggingface.co/papers/2604.04323) — How Well Do Agentic Skills Work in the Wild: Benchmarking LLM Skill Usage in Realistic Settings
- **日期**:2026-04-08 · **👍** 40 · **机构**:Shiyu's Lab · **Code**:[UCSB-NLP-Chang/Skill-Usage](https://github.com/UCSB-NLP-Chang/Skill-Usage)
- **AI Summary**:Research demonstrates that skill utilization in LLM-based agents degrades significantly under realistic conditions where skills must be retrieved and refined rather than handcrafted, though targeted refinement strategies can partially restore performance.

### [2604.05333](https://huggingface.co/papers/2604.05333) — Graph of Skills: Dependency-Aware Structural Retrieval for Massive Agent Skills
- **日期**:2026-04-10 · **👍** 22 · **机构**:University of Pennsylvania · **Code**:[davidliuk/graph-of-skills](https://github.com/davidliuk/graph-of-skills)
- **AI Summary**:Graph of Skills (GoS) enables efficient inference in large skill libraries by constructing executable skill graphs and retrieving dependency-aware bundles through hybrid retrieval methods, significantly improving reward performance while reducing token usage.

---

## 汇总表

| ID | 标题 | 日期 | 👍 | 方向 |
|---|---|---|---|---|
| [2602.01983](https://huggingface.co/papers/2602.01983) | Tool User → Creator (Training-Free Experience Reuse) | 2026-02-03 | 2 | 合成 |
| [2602.03279](https://huggingface.co/papers/2602.03279) | Agentic Proposing (Compositional Skill Synthesis) | 2026-02-03 | 0 | 合成 |
| [2602.05832](https://huggingface.co/papers/2602.05832) | UI-Mem (Self-Evolving Experience Memory) | 2026-02-05 | 0 | 记忆 |
| [2602.08004](https://huggingface.co/papers/2602.08004) | Data-Driven Analysis of Claude Skills | 2026-02-10 | 5 | 分析 |
| [2602.08234](https://huggingface.co/papers/2602.08234) | SkillRL (Recursive Skill-Augmented RL) | 2026-02-11 | 74 | 自进化 |
| [2602.12430](https://huggingface.co/papers/2602.12430) | Agent Skills 综述:架构/获取/安全 | 2026-02-12 | 1 | 综述 |
| [2602.12670](https://huggingface.co/papers/2602.12670) | SkillsBench | 2026-02-18 | 60 | 评测 |
| [2602.21320](https://huggingface.co/papers/2602.21320) | Tool-R0 (Zero-Data Self-Evolving Tool Learning) | 2026-03-03 | 12 | 自进化 |
| [2603.01145](https://huggingface.co/papers/2603.01145) | AutoSkill (Lifelong Skill Self-Evolution) | 2026-03-01 | 0 | 沉淀 |
| [2603.02176](https://huggingface.co/papers/2603.02176) | AgentSkillOS (Ecosystem-Scale Orchestration) | 2026-03-02 | 2 | 管理 |
| [2603.02766](https://huggingface.co/papers/2603.02766) | EvoSkill (Automated Skill Discovery) | 2026-03-03 | 1 | 合成 |
| [2603.05578](https://huggingface.co/papers/2603.05578) | Tool-Genesis (Tool Creation Benchmark) | 2026-03-05 | 0 | 评测 |
| [2603.09716](https://huggingface.co/papers/2603.09716) | AutoAgent (Cognition + Elastic Memory) | 2026-03-10 | 0 | 记忆 |
| [2603.12056](https://huggingface.co/papers/2603.12056) | XSkill (Experience + Skill Dual-Stream Continual Learning) | 2026-03-12 | 33 | 沉淀 |
| [2603.16060](https://huggingface.co/papers/2603.16060) | ARISE (Intrinsic Skill Evolution) | 2026-03-18 | 3 | 自进化 |
| [2603.17187](https://huggingface.co/papers/2603.17187) | MetaClaw (Meta-Learn in the Wild) | 2026-03-19 | 138 | 元学习 |
| [2603.18000](https://huggingface.co/papers/2603.18000) | AgentFactory (Subagent Accumulation) | 2026-03-18 | 0 | 沉淀 |
| [2603.18743](https://huggingface.co/papers/2603.18743) | Memento-Skills (Agents Design Agents) | 2026-03-20 | 57 | 自进化 |
| [2603.19461](https://huggingface.co/papers/2603.19461) | Hyperagents (Self-Referential Framework) | 2026-03-23 | 50 | 元学习 |
| [2603.22455](https://huggingface.co/papers/2603.22455) | SkillRouter (Retrieve-and-Rerank) | 2026-03-23 | 2 | 检索 |
| [2603.24533](https://huggingface.co/papers/2603.24533) | UI-Voyager (Self-Evolving GUI via Failure) | 2026-03-26 | 47 | 自进化 |
| [2603.24639](https://huggingface.co/papers/2603.24639) | Experiential Reflective Learning | 2026-03-25 | 3 | 沉淀 |
| [2603.25158](https://huggingface.co/papers/2603.25158) | Trace2Skill (Trajectory → Transferable Skill) | 2026-03-30 | 50 | 合成 |
| [2604.02268](https://huggingface.co/papers/2604.02268) | SKILL0 (In-Context Skill Internalization) | 2026-04-03 | 94 | 沉淀 |
| [2604.03964](https://huggingface.co/papers/2604.03964) | SKILLFOUNDRY (Self-Evolving Scientific Skill Lib) | 2026-04-05 | 0 | 沉淀 |
| [2604.04323](https://huggingface.co/papers/2604.04323) | LLM Skill Usage in the Wild | 2026-04-08 | 40 | 评测 |
| [2604.04804](https://huggingface.co/papers/2604.04804) | SkillX (Auto Skill KB Construction) | 2026-04-07 | 32 | 沉淀 |
| [2604.05333](https://huggingface.co/papers/2604.05333) | Graph of Skills (Dependency-Aware Retrieval) | 2026-04-10 | 22 | 检索 |

---

*获取单篇 Markdown 全文*:`hf papers read <PAPER_ID>`
