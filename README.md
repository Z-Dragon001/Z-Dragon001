# Hi, I'm DRAGON 👋

**Master's student at Huazhong University of Science and Technology (HUST)**  
**Undergraduate studies:** Southwest University

I work on **long-term memory for LLMs, model routing, and Agent training and applications**, turning research ideas into working Python systems.

## 代表项目

### 🧠 [InfoBudget2 · 长期记忆与模型路由](https://github.com/Z-Dragon001/InfoBudget2)

研究如何在记忆提取质量与模型调用成本之间做出更好的选择。

- 实现对话主题切分、多档候选记忆提取，以及基于 Qdrant 的记忆存储与检索。
- 围绕 LoCoMo、LongMemEval 构建训练与评估流程。
- 当前探索能力条件化的质量预测与质量差距路由，保留强化学习路由作为实验对照。

### 🛍️ [ServiceAgent-RL · 电商客服 Agent 训练](https://github.com/Z-Dragon001/mini-customer-agent-rl)

围绕退换货、订单取消和地址修改等多轮客服任务，构建从教师示范、监督微调到强化学习与评测的训练流程。

- 基于 Qwen2.5-3B-Instruct，使用 LoRA SFT 与 GRPO 训练工具调用和多步决策能力。
- 接入 tau-bench retail 零售环境的 16 个工具，以任务成功和业务进度构建奖励。
- 在单张 RTX 4090 D 24GB 上开展训练，保存对话、工具反馈和逐任务评测记录。

### 🤝 [TradingAgents · 多智能体投研实践](https://github.com/Z-Dragon001/TradingAgents)

基于 [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)，探索多角色协作完成研究与决策的工作流。

- 串联行情、新闻、情绪、基本面分析，以及多空辩论与风险讨论。
- 围绕状态管理、执行观测和结构化输出梳理系统实现。
- 将历史决策与复盘记录接入后续分析，观察经验如何影响决策过程。

## 当前关注

- **记忆：** 长对话中哪些信息值得保留，如何组织与检索？
- **路由：** 如何根据任务与模型能力，在质量和成本之间做选择？
- **协作：** 如何让多个 Agent 的状态、证据与执行过程更清楚？

欢迎围绕这些项目交流研究思路与工程实现。
