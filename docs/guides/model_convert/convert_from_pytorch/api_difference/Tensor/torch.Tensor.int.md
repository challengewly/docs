## [ torch 参数更多 ] torch.Tensor.int

### [torch.Tensor.int](https://pytorch.org/docs/stable/generated/torch.Tensor.int.html?highlight=int#torch.Tensor.int)

```python
torch.Tensor.int(memory_format=torch.preserve_format)
```

### [paddle.Tensor.astype](https://www.paddlepaddle.org.cn/documentation/docs/zh/develop/api/paddle/Tensor_cn.html#astype-dtype)

```python
paddle.Tensor.astype('int32')
```

Pytorch 相比 Paddle 支持更多其他参数，具体如下：

### 参数映射

| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| memory_format | - |表示内存格式，Paddle 无此参数，一般对网络训练结果影响不大，可直接删除。 |
