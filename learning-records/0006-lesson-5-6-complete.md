---
date: 2026-06-24
lesson: 5 (Context Engineering) + 6 (RAG Basics)
status: completed
---

# 第 5-6 课学习记录

## 已掌握
- Context Engineering vs Prompt Engineering 的概念转变（从写好指令 → 设计好上下文系统）
- Token 预算管理的原则（System Prompt 精简、RAG 结果占大头、留安全余量）
- RAG 五步流程：文档预处理 → 用户提问 → 向量检索 → 拼装 Prompt → 生成
- Embedding 模型的选型（BGE-M3 中文首选）
- Chunking 策略（固定大小、语义、递归、父子切分）
- 向量数据库选型（ChromaDB 适合中小规模）

## 用户反馈
- 内容偏浅：用户有搜索引擎开发经验，ANN/KNN 向量召回是已有知识
- 考题问题：正确选项总是明显比其他选项长，靠字符串长度就能猜答案
- 要求：后续课程加深难度，考题选项长度统一，增加更有区分度的题型（代码填空、数值计算等）

## 教学调整
- 第 7 课 RAG 进阶：压缩向量检索基础回顾，聚焦混合检索 + Reranker + GraphRAG 的增量知识
- 考题改进：选项长度统一、引入非选择题型、增加场景判断和代码题
