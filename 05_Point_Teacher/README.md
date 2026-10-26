# Point Teacher（2025）

**论文题目：** Tiny Object Detection with Single Point Supervision

**期刊：** ISPRS Journal of Photogrammetry and Remote Sensing，227：219–233，2025。

**DOI：** [10.1016/j.isprsjprs.2025.05.006](https://doi.org/10.1016/j.isprsjprs.2025.05.006)

**状态：** 已收录代码，尚未开始复现。

## 代码

- [本目录代码](code/)
- [个人 Fork](https://github.com/lee1992953779/Point-Teacher)
- [官方代码仓库](https://github.com/ZhuHaoranEIS/Point-Teacher)

## 阅读重点

开始进入弱监督检测。关注只有单点标注时如何生成目标框、教师学生网络如何逐步改善伪框，以及点位置噪声如何影响训练。对照常规全监督 YOLO，明确训练标签形式的区别。

## 待完成

理解两阶段去噪学习流程 → 核对数据集单点标注生成方式 → 运行上游示例 → 记录点标注噪声与检测结果。
