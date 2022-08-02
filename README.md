# Awesome Nerf 3D Reconstruction

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) [![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A curated list of NeRF and Implicit Representations papers for 3D Reconstruction, inspired by [
awesome-neural-rendering](https://github.com/weihaox/awesome-neural-rendering).

Any contributions are much appreciated, please feel free to [pull a request](https://github.com/imbinwang/awesome-nerf-3d-reconstruction/pulls) and offer the paper information as following format:

``` markdown
**Title of Paper.**<br>
*Author 1, Author 2, and Author 3.*<br>
Conference or Journal Year. [[PDF](link)] [[Project](link)] [[Github](link)] [[Video](link)] [[Data](link)]
```

## Table of Contents</summary>

- [Papers](#papers)
- [Related Resources](#related-resources)
- [Other Awesome Lists](#other-awesome-lists)

## Papers

**SparseNeuS: Fast Generalizable Neural Surface Reconstruction from Sparse views.**<br>
*Xiaoxiao Long, Cheng Lin, Peng Wang, Taku Komura, Wenping Wang.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2206.05737)] [[Project](https://www.xxlong.site/SparseNeuS/)] [[Github](https://github.com/xxlong0/SparseNeuS)]

**NeuRIS: Neural Reconstruction of Indoor Scenes Using Normal Priors.**<br>
*Jiepeng Wang, Peng Wang, Xiaoxiao Long, Christian Theobalt, Taku Komura, Lingjie Liu, Wenping Wang.*<br>
arXiv preprint 2022. [[PDF](https://arxiv.org/abs/2206.13597)] [[Project](https://jiepengwang.github.io/NeuRIS/)]

**BNV-Fusion: Dense 3D Reconstruction using Bi-level Neural Volume Fusion.**<br>
*Kejie Li, Yansong Tang, Victor Adrian Prisacariu, Philip H.S. Torr.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2204.01139)] [[Github](https://github.com/likojack/bnv_fusion)] [[Video](https://www.youtube.com/watch?v=ptx5vtQ9SvM)]

**NeRFusion: Fusing Radiance Fields for Large-Scale Scene Reconstruction.**<br>
*Xiaoshuai Zhang, Sai Bi, Kalyan Sunkavalli, Hao Su, Zexiang Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.11283)] [[Project](https://jetd1.github.io/NeRFusion-Web/)] [[Github](https://github.com/jetd1/NeRFusion)]

**Urban Radiance Fields.**<br>
*Konstantinos Rematas, Andrew Liu, Pratul P. Srinivasan, Jonathan T. Barron, Andrea Tagliasacchi, Thomas Funkhouser, Vittorio Ferrari.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2111.14643)] [[Project](https://urban-radiance-fields.github.io/)]

**Neural RGB-D Surface Reconstruction.**<br>
*Dejan Azinović, Ricardo Martin-Brualla, Dan B Goldman, Matthias Nießner, Justus Thies.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2104.04532)] [[Project](https://dazinovic.github.io/neural-rgbd-surface-reconstruction/)] [[Github](https://github.com/dazinovic/neural-rgbd-surface-reconstruction)]

**Neural 3D Scene Reconstruction with the Manhattan-world Assumption.**<br>
*Haoyu Guo, Sida Peng, Haotong Lin, Qianqian Wang, Guofeng Zhang, Hujun Bao, Xiaowei Zhou.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2205.02836)] [[Project](https://zju3dv.github.io/manhattan_sdf/)] [[Github](https://github.com/zju3dv/manhattan_sdf)]

**Neural 3D Reconstruction in the Wild.**<br>
*Jiaming Sun, Xi Chen, Qianqian Wang, Zhengqi Li, Hadar Averbuch-Elor, Xiaowei Zhou, Noah Snavely.*<br>
SIGGRAPH 2022. [[PDF](https://arxiv.org/abs/2205.12955)] [[Project](https://zju3dv.github.io/neuralrecon-w/)] [[Github](https://github.com/zju3dv/NeuralRecon-W)]

**iSDF: Real-Time Neural Signed Distance Fields for Robot Perception.**<br>
*Joseph Ortiz, Alexander Clegg, Jing Dong, Edgar Sucar, David Novotny, Michael Zollhoefer, Mustafa Mukadam.*<br>
RSS 2022. [[PDF](https://arxiv.org/abs/2204.02296)] [[Project](https://joeaortiz.github.io/iSDF/)] [[Github](https://github.com/facebookresearch/iSDF)]

**Volume Rendering of Neural Implicit Surfaces.**<br>
*Lior Yariv, Jiatao Gu, Yoni Kasten, Yaron Lipman.*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2106.12052)] [[Project](https://lioryariv.github.io/volsdf/)] [[Github](https://github.com/lioryariv/volsdf)]

**NeuS: Learning Neural Implicit Surfaces by Volume Rendering for Multi-view Reconstruction.**<br>
*Peng Wang, Lingjie Liu, Yuan Liu, Christian Theobalt, Taku Komura, Wenping Wang.*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2106.10689)] [[Project](https://lingjie0206.github.io/papers/NeuS/index.htm)] [[Github](https://github.com/Totoro97/NeuS)]

**UNISURF: Unifying Neural Implicit Surfaces and Radiance Fields for Multi-View Reconstruction.**<br>
*Michael Oechsle, Songyou Peng, Andreas Geiger.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2104.10078)] [[Project](https://moechsle.github.io/unisurf/)] [[Github](https://github.com/autonomousvision/unisurf)]

**Multiview Neural Surface Reconstruction by Disentangling Geometry and Appearance.**<br>
*Lior Yariv, Yoni Kasten, Dror Moran, Meirav Galun, Matan Atzmon, Ronen Basri, Yaron Lipman.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2003.09852)] [[Project](https://lioryariv.github.io/idr/)] [[Github](https://github.com/lioryariv/idr)]

**Occupancy Networks: Learning 3D Reconstruction in Function Space.**<br>
*Lars Mescheder, Michael Oechsle, Michael Niemeyer, Sebastian Nowozin, Andreas Geiger.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1812.03828)] [[Github](https://github.com/autonomousvision/occupancy_networks)]

**DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation.**<br>
*Jeong Joon Park, Peter Florence, Julian Straub, Richard Newcombe, Steven Lovegrove.*<br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1901.05103)] [[Github](https://github.com/facebookresearch/DeepSDF)]

## Related Resources

**Advances in Neural Rendering.**<br>
*Ayush Tewari, Justus Thies, Ben Mildenhall, Pratul Srinivasan, Edgar Tretschk, Yifan Wang, Christoph Lassner, Vincent Sitzmann, Ricardo Martin-Brualla, Stephen Lombardi, Tomas Simon, Christian Theobalt, Matthias Niessner, Jonathan T. Barron, Gordon Wetzstein, Michael Zollhoefer, Vladislav Golyanik.*<br>
EUROGRAPHICS 2022 State of the Art Report. [[PDF](https://arxiv.org/abs/2111.05849)]

**Neural Fields in Computer Vision.**<br>
CVPR 2022 Tutorial. [[Project](https://neuralfields.cs.brown.edu/cvpr22.html)]

**Advances in Neural Rendering.**<br>
SIGGRAPH 2021 Course. [[Project](https://www.neuralrender.com/)]

**[NeRF at CVPR 2022](https://dellaert.github.io/NeRF22/)**

**[neurecon](https://github.com/ventusff/neurecon)**

**[NeRF：用深度学习完成3D渲染任务的蹿红](https://zhuanlan.zhihu.com/p/390848839?utm_source=im.xinda.youdu&utm_medium=social&utm_oi=43102693752832)**

**[Neural Radiance Field’s Volume Rendering 公式分析](https://raymondkevin.top/2021/07/22/neural-radiance-fields-volume-rendering-%E5%85%AC%E5%BC%8F%E5%88%86%E6%9E%90/)**

## Other Awesome Lists

**[Awesome 3D Reconstruction](https://github.com/openMVG/awesome_3DReconstruction_list)**

**[Awesome Neural Rendering](https://github.com/weihaox/awesome-neural-rendering)**

**[Awesome Neural Radiance Fields](https://github.com/yenchenlin/awesome-NeRF)**

**[Awesome Implicit NeRF Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)**
