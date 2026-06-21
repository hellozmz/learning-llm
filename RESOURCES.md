# 大模型学习资源

## Knowledge

### 入门与概览
- [在线书籍: _LLM Engineer's Handbook_ — Paul Iusztin & Maxime Labonne](https://github.com/PacktPublishing/LLM-Engineers-Handbook)
  从数据工程到推理部署的全流程实战手册。适合：了解 LLM 工程全貌，找到自己感兴趣的方向。

- [课程: _CS25: Transformers United_ — Stanford](https://web.stanford.edu/class/cs25/)
  Stanford 的 Transformer 专题研讨会，每期邀请不同嘉宾讲解最新进展。适合：了解前沿动态。

### 深度学习基础
- [在线书籍: _Dive into Deep Learning_ — 李沐等 (d2l.ai)](https://d2l.ai/)
  互动式深度学习教材，代码+公式+图示三位一体，有中文版。适合：从零补深度学习基础。

- [视频: _李宏毅 机器学习 2023_ — YouTube](https://www.youtube.com/@HungyiLeeNTU)
  台大李宏毅教授的机器学习课程，中文授课，讲解清晰。适合：系统学习 ML/DL 基础。

### Transformer & LLM 原理
- [视频: _Let's build GPT from scratch_ — Andrej Karpathy (YouTube)](https://www.youtube.com/watch?v=kCc8FmEb1nY)
  Karpathy 手写 GPT，从空文件开始。适合：理解 Tokenization、Attention、Transformer Block、生成过程。

- [交互可视化: _Transformer Explainer_](https://poloclub.github.io/transformer-explainer/) / [中文版](https://explainer.tubex.chat/)
  可输入文字实时查看 Q/K/V 投影和 Attention 权重分配。适合：直观理解 Self-Attention 的"答案在题目中"机制。

- [文章: _The Illustrated Transformer_ — Jay Alammar](https://jalammar.github.io/illustrated-transformer/)
  最经典的 Transformer 图解，直观展示 Q/K/V、Multi-Head Attention。适合：首次接触 Transformer。
  最经典的 Transformer 图解，直观展示 Q/K/V、Multi-Head Attention。适合：首次接触 Transformer。

- [文章: _Attention Is All You Need_ 论文精读 — 李沐 (B站)](https://www.bilibili.com/video/BV1pu411o7BE/)
  李沐逐页精读 Transformer 原论文。适合：深入理解论文细节。

- [在线书籍: _Build a Large Language Model (From Scratch)_ — Sebastian Raschka](https://www.manning.com/books/build-a-large-language-model-from-scratch)
  从头构建 LLM 的完整教程，代码驱动。适合：动手实现。

### 应用开发 (RAG/Agent)
- [文档: _LangChain 官方文档_](https://python.langchain.com/docs/)
  LangChain 是 LLM 应用开发的事实标准框架。适合：搭建 RAG/Agent/Chain 应用。

- [文档: _LlamaIndex 官方文档_](https://docs.llamaindex.ai/)
  专注数据索引和检索的框架，RAG 场景更专业。适合：构建复杂 RAG pipeline。

- [课程: _DeepLearning.AI: LangChain Chat with Your Data_](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/)
  Andrew Ng 与 LangChain 作者的免费短课。适合：快速上手 RAG。

### 微调与部署
- [GitHub: _LLaMA-Factory_](https://github.com/hiyouga/LLaMA-Factory)
  最流行的 LLM 微调框架，支持 LoRA/QLoRA/全参微调。适合：微调实战。

- [GitHub: _vLLM_](https://github.com/vllm-project/vllm)
  高性能 LLM 推理引擎，PagedAttention。适合：生产级模型部署。

- [文章: _A Visual Guide to Quantization_ — Maarten Grootendorst](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-quantization)
  图解量化原理（从 FP16 到 GGUF/AWQ/GPTQ）。适合：理解量化。

- [GitHub: _unsloth_](https://github.com/unslothai/unsloth)
  加速微调 2-5x，降低显存占用。适合：资源有限的微调场景。

## Wisdom (Communities)

- [r/LocalLLaMA (Reddit)](https://reddit.com/r/LocalLLaMA)
  本地模型部署和微调的最高质量社区。适合：遇到部署/量化/微调问题时找答案。

- [WayToAGI 知识库](https://waytoagi.feishu.cn/wiki/QPe5w5g7UisjEIkV7OycbqBJn3c)
  中文 AI 学习路线图，系统整理了大量资料。适合：找中文学习路径指引。

- [Hugging Face Daily Papers](https://huggingface.co/papers)
  HF 每日精选论文。适合：追踪前沿研究。

## Gaps
- 中文世界缺乏高质量的 Transformer 实现逐行讲解（李沐的论文精读偏理论，Karpathy 的偏代码）
- 缺乏针对金融/NL2SQL 场景的 LLM 应用最佳实践资料
