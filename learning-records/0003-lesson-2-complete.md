# 第2课完成：MLP + 反向传播 + PyTorch 自动微分

用户确认理解：
- n 层 MLP = n 次 GEMM + (n-1) 次激活，输出层不加 ReLU
- loss.backward() 只算梯度存入 .grad，不更新参数
- optimizer.step() 才执行参数更新
- optimizer.zero_grad() 必须显式调用，否则梯度累加
- .grad 是 requires_grad=True 的 Tensor 的属性

用户披露：有多年的模型训练和推理实际工作经验。

Implications: 后续课程可以加快节奏，加大深度。工程概念（优化器、显存、推理部署）不需要从零解释。
