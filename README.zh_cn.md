![Baidu Logo](/doc/baidu-research-logo-small.png)

[In English](README.md)

# warp-ctc

在我们实验室，我们专注于将递归神经网络规模化, CTC损失函数是其中很重要的一部分。为了让我们的系统更有效率，我们并行处理了CTC算法，正如这篇文章中所描述的（http://arxiv.org.abs/1512.02595）
。这个项目包含了我们的高性能CPU以及CUDA版本的CTC损失函数, 以及绑定的Torch （http://torch.ch/）. 该代码库提供了简单的C接口，易于与深度学习框架整合。
