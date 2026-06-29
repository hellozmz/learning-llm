---
date: 2026-06-29
lesson: 11 (Eval + 可观测性)
status: completed
---

# 第 11 课学习记录

## 已掌握
- LLM 评估与传统 ML 评估的本质差异（输出非结构化，无法用 exact match）
- Golden Set 构造的三层结构：事实题 / 推理题 / 边界题
- LLM-as-judge 模式 + 三大偏置（位置 / 长度 / 自我偏好）
- RAG 评估框架 Ragas 的四维度：Faithfulness / Answer Relevance / Context Precision / Context Recall
- Agent 评估的三层次：工具选择准确率 / 参数正确率 / 端到端任务完成率
- 在线可观测性：Trace 链路 + 四核心指标（Token / Latency / Tool Success / Error Rate）
- 工具选型：Langfuse（自部署）适合可转债项目，数据不出内网
- 回归测试：CI 流水线里跑 golden set，比 baseline 不允许退化超过 5%

## 用户延展讨论（第 10 课相关）
- ReAct vs CoT：CoT 是纯推理，ReAct = CoT + 工具行动 + 外部观察
- ReAct/Plan-and-Execute 不需要特殊训练模型，是 prompt + 循环代码层面的事
- Agent = loop engineering 的本质（while 循环 + 消息管理 + 工具分发 + 错误处理）
- 多 Agent 的合理场景补充：双会话独立分析（上下文隔离的并行视角）vs 单会话辩论（不推荐）

## 教学调整记录
- 用户对题目 3（多 Agent 决策）的选项 D 提出质疑：300 只转债并行本质是数据并行而非多 Agent 架构。已在对话中承认表述不够严谨，补充"上下文隔离的双会话独立分析"作为多 Agent 的合理场景
- 用户思维敏锐度高于预设，未来课程应避免"看似简单但选项表述不严谨"的题目
