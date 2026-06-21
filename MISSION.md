# Mission: 系统掌握大模型技术栈

## Why
在可转债量化平台中引入大模型能力（智能分析、NL2SQL、报告生成），同时具备独立开发 RAG/Agent 应用和部署微调开源模型的能力。不再只是"会跑模型"，而是能从容地读论文、改源码、选架构。

## Success looks like
- 能解释 Transformer 完整计算图（注意力头、FFN、残差、LayerNorm），并手写一个可训练的微型 GPT
- 能用 LangChain/LlamaIndex 从零搭建一个 RAG 应用，并说出向量库/chunking/检索策略的选择理由
- 能用 LoRA/QLoRA 在自己的数据上微调一个 7B 模型，并量化部署到单卡
- 在可转债项目中至少落地一个 LLM 驱动的功能模块

## Constraints
- 每天 1-2 小时，碎片时间为主
- Python 熟练，numpy/pandas 熟练，深度学习零基础
- 已有跑开源模型的经验（ollama/vLLM 等），但缺乏系统理论
- 学习资料以中文为主、英文为辅

## Out of scope
- 预训练 from scratch（算力不可行）
- 多模态模型（视觉/语音），当前聚焦纯文本
- RLHF/DPO 等对齐技术的高级细节（先掌握基础再深入）
