# PointOBB-v3（2025）

**一句话简介：** 通过多视图学习单点监督的旋转目标检测。

**论文题目：** PointOBB-v3: Expanding Performance Boundaries of Single Point-Supervised Oriented Object Detection

**期刊：** International Journal of Computer Vision，133：6108–6128，2025。

**DOI：** [10.1007/s11263-025-02486-4](https://doi.org/10.1007/s11263-025-02486-4)

**状态：** 已收录代码，尚未开始复现。

## 代码

- [本目录代码](code/)
- [个人 Fork](https://github.com/lee1992953779/PointOBB-v3)
- [官方代码仓库](https://github.com/VisionXLab/PointOBB-v3)

官方仓库分别提供两阶段版本与端到端版本；运行前需确认所用分支和配置。

## 阅读重点

与 Wholly-WOOD 对照阅读。重点看单点标注如何推断目标尺度与角度，多视图和尺度一致性各自解决什么问题，以及端到端版本如何调整训练流程。

## 待完成

明确版本与分支 → 阅读尺度和角度学习模块 → 核对数据与配置 → 运行并记录不同训练方案的实际结果。
