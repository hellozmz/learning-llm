# NOTES.md — 教学偏好与备忘

## 用户偏好
- 语言：中文授课，术语保留英文
- 节奏：每天 1-2 节，每节 30-40 分钟
- 风格：理论 + 代码并重，先理解原理再动手
- 反馈：喜欢被提问检验理解，不怕犯错
- 难度：有多年的模型训练和推理工作经验，课程可加深

## 已知基础
- Python/numpy/pandas 熟练，有模型训练推理经验
- Transformer/GPT 架构已系统掌握（基础篇 4 课完成）
- **有搜索引擎开发经验，用过 KNN/ANN 做向量召回** — RAG 的向量检索部分不是新知识
- 目标：在可转债项目中落地 LLM 功能模块

## 用户反馈与调整（2026-06-24）
- **考题问题**：正确选项总是明显比其他选项长，靠长度就能猜。后续所有考题要求：选项长度统一，不做"长即正确"
- **深度问题**：5、6 两课内容偏浅，用户有搜索/ANN 背景。后续课程：压缩已掌握内容，聚焦真正增量知识
- **考题难度**：用户要求更难、更有区分度的题目。可引入代码填空、数值计算、场景判断题

## 教学规划（2026-06 更新，基于业界调研）

### 基础篇 ✅ 已完成
1. ✅ 神经元 + 激活函数 + 梯度下降
2. ✅ MLP + 反向传播 + PyTorch 训练循环
3. ✅ Self-Attention（Q/K/V, Multi-Head, Causal Mask, O(n²)）
4. ✅ GPT-2 完整架构（Embedding → N×Block → LM Head, KV Cache）

### 应用篇：RAG + Agent 技术栈（2026 业界主流）
5. Prompt Engineering → Context Engineering（从写提示词到设计上下文）
6. RAG 基础：Embedding + 向量检索 + 生成全链路
7. RAG 进阶：混合检索 + Reranker + GraphRAG（金融文档核心能力）
8. Function Calling + Tool Use（让模型调用你的 Python 函数）
9. MCP 协议：标准化 Agent-工具接入
10. Agent 设计模式（ReAct, Plan-and-Execute, 单Agent vs 多Agent）

### 工程篇：部署与微调
11. Eval + 可观测性（模型效果评估与生产监控）
12. vLLM 推理部署（PagedAttention, Continuous Batching, API 服务化）
13. LoRA/QLoRA 微调 + 量化（GGUF/AWQ）
14. 可转债项目实战（LLM 功能模块落地）

### 2026 关键判断（来源：O'Reilly Agent Stack 2026 等）
- RAG 已进化：纯向量检索不够 → 混合检索 + Reranker 是标配 → GraphRAG 是高端方案
- Agent 不用上来就多Agent → 先做好单Agent + 好工具
- MCP 已是工具接入标准协议（月下载 97M）
- 框架选 LangGraph 前先问"真的需要状态图吗" → 多数场景 Provider SDK + MCP 就够了
