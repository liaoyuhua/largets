<div align="center">

[![GitHub stars](https://img.shields.io/badge/coming-soon-orange.svg)](
)
[![license](https://img.shields.io/github/license/liaoyuhua/largets.svg)](https://github.com/liaoyuhua/largets/blob/main/LICENSE) [![developping](https://img.shields.io/badge/developing-yes-green.svg)]()
[![GitHub stars](https://img.shields.io/github/stars/liaoyuhua/largets.svg?style=social&label=Stars)](
)


# LargeTS

English | [简体中文](README_zh.md)


Train time series models on large-scale data.

</div>

Typically, a single time series is not too large to load and train. However, when we have a large number of time series (100M or more), a lot of disk space, memory and computing resources are required to train the model. LargeTS is a framework that solves this problem. It provides solutions from data processing to model training. The main components are:

> data: this module is based on a space-efficient design that can load data from disk and train models without loading all data into memory.

> model: this module provides a transformer-based model for time series.

> engine: this module provides a pipeline to train models on large-scale data. With acceleration methods, we can train models on large-scale data in an acceptable time.
