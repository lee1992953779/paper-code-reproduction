# NWD-RKA（2022）

**一句话简介：** 用 Wasserstein 距离改进航拍微小目标检测。

**论文题目：** Detecting tiny objects in aerial images: A normalized Wasserstein distance and a new benchmark

**期刊：** ISPRS Journal of Photogrammetry and Remote Sensing，190：79–93，2022。

**DOI：** [10.1016/j.isprsjprs.2022.06.002](https://doi.org/10.1016/j.isprsjprs.2022.06.002)

**状态：** 已收录代码，尚未开始复现。

## 代码

- [本目录代码](code/)
- [个人 Fork](https://github.com/lee1992953779/mmdet-aitod)
- [官方代码仓库](https://github.com/Chasel-Tsui/mmdet-aitod)

官方实现位于 `mmdet-aitod` 仓库，包含 `mmdet-nwdrka` 目录。`AI-TOD-v2` 项目网页仓库不替代这里的算法代码。

## 阅读重点

先略读，重点理解：为什么同样几像素的位置偏移对小目标的 IoU 影响更大；NWD 如何衡量框之间的距离；RKA 如何为小目标分配训练样本。把它作为后续 SWIN-TOD 的基础。

## 待完成

阅读方法与消融实验 → 核对上游运行说明 → 准备 AI-TOD-v2 数据与评价方式 → 运行并记录结果。
