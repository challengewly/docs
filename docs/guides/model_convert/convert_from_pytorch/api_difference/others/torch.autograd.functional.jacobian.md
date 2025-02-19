## [torch 参数更多]torch.autograd.functional.jacobian

### [torch.autograd.functional.jacobian](https://pytorch.org/docs/stable/generated/torch.autograd.functional.jacobian.html#torch.autograd.functional.jacobian)

```python
torch.autograd.functional.jacobian(func, inputs, create_graph=False, strict=False, vectorize=False, strategy='reverse-mode')
```

### [paddle.incubate.autograd.Jacobian](https://www.paddlepaddle.org.cn/documentation/docs/zh/develop/api/paddle/incubate/autograd/Jacobian_cn.html)

```python
paddle.incubate.autograd.Jacobian(func, xs, is_batched=False)
```

Pytorch 相比 Paddle 支持更多其他参数，具体如下：

### 参数映射

| PyTorch      | PaddlePaddle | 备注                                                                |
| ------------ | ------------ | ------------------------------------------------------------------- |
| func         | func         | Python 函数。                                                       |
| inputs       | xs           | 函数 func 的输入参数。                                              |
| create_graph | -            | 是否创建图，Paddle 无此参数，暂无转写方式。     |
| strict       | -            | 是否在存在一个与所有输出无关的输入时抛出错误，Paddle 无此参数，暂无转写方式。 |
| vectorize    | -            | 体验中功能，Paddle 无此参数，暂无转写方式。         |
| strategy     | -            | AD 计算模式，Paddle 无此参数，暂无转写方式。          |
| -            | is_batched   | 表示包含 batch 维，PyTorch 无此参数，Paddle 保持默认即可。          |
