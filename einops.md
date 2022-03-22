einops 张量操作神器（支持PyTorch)
https://github.com/arogozhnikov/einops


https://www.icode9.com/content-4-946796.html




## 简介

- einops是一个用于操作张量的库，它的出现可以替代我们平时使用的reshape、view、transpose和permute等操作，相信接触过深度学习的同学一定对这些函数比较的熟悉。

- einops相较于上面说的那些函数，最显著的区别就是逻辑更加的清晰，用网上的一句话来说的话，就是可以避免view、transpose等函数的神秘主义🤦‍♂️

- 第一次看见别人用einops这个库是在看ViT代码的时候，在简单的使用之后，感觉确实会比一般的维度操作工具更加的方便和直观，所以这里就einops的使用做一个简单的介绍
