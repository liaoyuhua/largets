<div align="center">

[![GitHub stars](https://img.shields.io/badge/coming-soon-orange.svg)](
)
[![license](https://img.shields.io/github/license/liaoyuhua/largets.svg)](https://github.com/liaoyuhua/largets/blob/main/LICENSE) [![developping](https://img.shields.io/badge/developing-yes-green.svg)]()
[![GitHub stars](https://img.shields.io/github/stars/liaoyuhua/largets.svg?style=social&label=Stars)](
)

# LargeTS

[English](README.md) | 简体中文

在大规模数据上训练时间序列模型。

</div>

通常，单条时间序列不会大到无法加载和训练。但是，当我们有大量时间序列（100M或更多）时，需要大量的磁盘空间、内存和计算资源来训练模型。LargeTS是一个解决这个问题的框架，提供了从数据处理到模型训练的解决方案。主要组件有：

> data：该模块基于空间高效的设计，可以从磁盘加载数据并训练模型，而无需将所有数据加载到内存中。

> model：该模块为时间序列提供了基于transformer的模型。

> engine：该模块提供了一个管道，用于在大规模数据上训练模型。通过加速方法，我们可以在可接受的时间内在大规模数据上训练模型。
