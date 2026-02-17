# AI 公司博客周报 (2026-02-02 至 2026-02-08)

> 监控日期: 2026-02-15 | 范围: 上周 (周一至周日)

## 符合用户兴趣的文章

### Microsoft Research

#### 1. Rethinking Imitation Learning with Predictive Inverse Dynamics Models

- **发布日期**: 2026-02-05
- **URL**: https://www.microsoft.com/en-us/research/blog/rethinking-imitation-learning-with-predictive-inverse-dynamics-models/
- **来源**: Microsoft Research Blog

**内容摘要**:
研究 Predictive Inverse Dynamics Models (PIDMs) 为何优于标准 Behavior Cloning。PIDMs 将问题分解为两个子问题：
1. 预测未来状态 (what should happen next)
2. 推断从当前状态到未来状态所需的动作 (inverse dynamics)

核心洞见：即使预测不完美，只要误差不大，PIDMs 仍优于 BC。实验表明只需 BC 所需演示数量的 1/5 即可达到相当性能。

**为何关注**:
- RL 训练范式 (Imitation Learning)
- 数学推导、理论分析 (为何有效)
- 数据效率提升

**初步评价**: 理论分析扎实，提供了清晰的数学直觉，适合关注 RL 演进和理论推导的读者。

---

### Surge AI

#### 2. Building AdvancedIF: Evolving Instruction Following Beyond IFEval and "Avoid the Letter C"

- **发布日期**: 2026-02-04
- **URL**: https://surgehq.ai/blog
- **来源**: Surge AI Blog (与 Meta Superintelligence Labs 合作)

**内容摘要**:
与 Meta Superintelligence Labs 合作构建 AdvancedIF 基准测试：
- 每个 prompt 和评分规则都由人类专家撰写（而非 LLM 合成生成）
- 在指令遵循领域，前沿模型仍失败 22-30%
- 使用人类撰写的评分规则作为 RL 奖励信号可获得 **13%** 的提升

**为何关注**:
- **数据构建**: 人类撰写的评分规则
- **Benchmark**: 指令遵循新基准
- **RL**: 奖励信号设计

**初步评价**: 强调人工数据构建的重要性，13% 的提升显著，值得关注数据合成/筛选方法。

---

## 不直接符合兴趣的文章（仅列出）

### Anthropic
- Opus 4.6 升级公告 (2026-02-05) - 通用模型更新

### Surge AI
- Hemingway-bench Leaderboard (2026-02-06) - AI 写作评估
- RL Environments and the Hierarchy of Agentic Capabilities (2026-02-05)
- SWE-Bench Failures: When Coding Agents Spiral Into 693 Lines of Hallucinations (2026-02-05)

### LangChain
- 多篇 Agent 相关文章，但日期不明确

---

## 说明

- **日期范围计算**: 今天是 2026-02-15 (周日)，上周为 2026-02-02 (周一) 至 2026-02-08 (周日)
- 部分博客（Meta AI、Hugging Face）无法正常获取内容
- MIT Technology Review AI 文章未能成功抓取
