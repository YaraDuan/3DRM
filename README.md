# 3DRM:  Pair-wise Relation Module for 3D Object Detection
Created by Yuqin Lan, Yao Duan, Yifei Shi, Kai Xu.

## Introduction
3DRM is a plug-and-ply module which can be applied to different 3D detection frameworks to detect 3D objects more accurately and robustly. We implement two applications on proposal-based methods and vote-based methods: OSegPointCNN (Over-segmentation to generate proposals and PointCNN as backbones) and VoteNet. OSegPointCNN is trained and evaluated on S3DIS dataset, and VoteNet is trained and evaluated on ScanNetV2 and SUN RGB-D dataset. For further information about the implemention, please refer to the sub-directories: [OSeg-PointCNN-RN](./OSeg-PointCNN-RN) and [VoteNet-RN](./VoteNet-RN).


## Acknowledgemets
This code largely benefits from excellent works [PointCNN](https://github.com/yangyanli/PointCNN) and [VoteNet](https://github.com/facebookresearch/votenet) and repositories, please also consider cite [PointCNN](https://arxiv.org/abs/1801.07791.pdf) and [VoteNet](https://arxiv.org/pdf/1904.09664.pdf) and  if you use this code.