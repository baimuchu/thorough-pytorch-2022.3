# Thorough-pytorch-2022.3 
# 深入浅出PyTorch（进阶）-2022年3月

## 第一次作业-Pytorch模型定义
本次作业主要完成了如下目标：
 - 关于Module类的学习，包括了3种方式，当然比较好用的还是Sequential方法。
 - 使用Module类搭建一个卷积神经网络，这里将U-Net作为主要实现目标。
 - 简单的模型操作，如何将一个已有的模型进行调整，关于输入和输出参数的调整。
 - 模型的运行与保存，使用GPU或CPU完成模型的运行。

## 第二次作业-PyTorch进阶训练技巧
本次作业主要完成了如下目标：
 - 使用函数或者类完成对损失函数的定义。
 - 使用scheduler API对学习率进行动态调整。
 - 模型微调：对源模型微调，对已有模型进行使用，训练特定层。
 - 半精度能够减少显存占用，使得显卡可以同时加载更多数据进行计算。

## 第三次作业-PyTorch可视化
本次作业主要完成了如下目标：
 - 通过使用torchinfo库对模型的参数进行可视化，包括模块信息（每一层的类型、输出shape和参数量）、模型整体的参数量、模型大小、一次前向或者反向传播需要的内存大小等可视化。
 - 如何对卷积核与特征图进行可视化操作。
 - 通过使用grad-cam库对class activation map （CAM）进行可视化，能够一目了然地确定重要区域，进而进行可解释性分析或模型优化改进。
 - 通过使用FlashTorch完成对CNN的进行可视化，包括卷积核、特征图、梯度进行可视化。
 - 使用Tensorboad工具对数据进行可视化，这个比较全能。可以对数据分析，AI都能做一些可视化工作。

## 学习与参考资料
[Datawhale-深入浅出PyTorch(进阶)](https://github.com/datawhalechina/thorough-pytorch)

[Pytorch中文文档](https://www.pytorchtutorial.com)

[Pytorch官方文档](https://pytorch.org/docs/stable/index.html)
