# SWIN-TOD（2024）

**论文题目：** SWIN-TOD: Smooth Wasserstein Distance and Instance-Level Neighboring Enhancement for Remote Sensing Tiny Object Detection

**期刊：** IEEE Transactions on Geoscience and Remote Sensing，62，5638915，2024。

**DOI：** [10.1109/TGRS.2024.3452010](https://doi.org/10.1109/TGRS.2024.3452010)

**状态：** 已收录代码，尚未开始复现。

## 代码

- [本目录代码](code/)
- [个人 Fork](https://github.com/lee1992953779/SWIN-TOD)
- [官方代码仓库](https://github.com/sevenwgb/SWIN-TOD)

官方仓库包含 `ForYOLO`，提供将方法接入 YOLOv5、YOLOv9 的参考代码。

## 阅读重点

建议作为第一篇重点阅读和复现的论文。先看实例级邻域增强网络如何聚合目标间信息，再看 Smooth Wasserstein Loss 如何改善小目标定位，最后对照模块消融实验判断各部分作用。

## 待完成

理解两个核心模块 → 核对 `ForYOLO` 接入位置和环境 → 运行基线 → 分别验证模块与损失 → 记录真实指标。
