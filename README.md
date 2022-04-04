[<img height="23" src="https://github.com/lh9171338/Outline/blob/master/icon.jpg"/>](https://github.com/lh9171338/Outline) Line Segment Detection Papers
===

A collection of line segment detection papers (*a.k.a.* wireframe parsing).

# Outline

- [Deep-Learning Based Approaches](#1-Deep-Learning-Based-Approaches)
  - [Line Segment Detection](#11-Line-Segment-Detection)
  - [Wireframe Parsing](#12-Wireframe-Parsing)
- [Traditional approaches](#2-Traditional-Approaches)
- [Datasets](#3-Datasets)

# 1. Deep Learning-Based Approaches

## 1.1 Line Segment Detection

| Name | Paper | Source | Resource |
| --- | --- | --- | --- |
| M-LSD | [Towards Real-time and Light-weight Line Segment Detection](https://arxiv.org/abs/2106.00186) | AAAI 2022 | [[Code]](https://github.com/navervision/mlsd) |
| ELSD | [ELSD: Efficient Line Segment Detector and Descriptor](https://ieeexplore.ieee.org/document/9710129) | ICCV 2021 | [[Code]](https://github.com/Tinyyyy/ELSD) |
| F-Clip | [Fully Convolutional Line Parsing](https://arxiv.org/abs/2104.11207v2) | ArXiv 2021 | [[Code]](https://github.com/Delay-Xili/F-Clip) |
| LETR | [Line Segment Detection Using Transformers without Edges](https://ieeexplore.ieee.org/document/9578142) | CVPR 2021 | [[Code]](https://github.com/mlpc-ucsd/LETR) |
| LS-Net | [LS-Net: fast single-shot line-segment detector](https://link.springer.com/article/10.1007/s00138-020-01138-6) | MVA 2021 |  |
| TP-LSD | [TP-LSD: Tri-Points Based Line Segment Detector](https://link.springer.com/chapter/10.1007/978-3-030-58583-9_46) | ECCV 2020 | [[Code]](https://github.com/MegviiRobot/TP-LSD) |
| LaRecNet | [Learning to Calibrate Straight Lines for Fisheye Image Rectification](https://ieeexplore.ieee.org/document/8954315) | CVPR 2019 | [[Project]](https://xuezhucun.github.io/LaRecNet/) |
| PPGNet | [PPGNet: Learning Point-Pair Graph for Line Segment Detection](https://ieeexplore.ieee.org/document/8954275) | CVPR 2019 | [[Code]](https://github.com/svip-lab/PPGNet) |
| AFM | [Learning Attraction Field Representation for Robust Line Segment Detection](https://ieeexplore.ieee.org/document/8954315) | CVPR 2019 | [[Code]](https://github.com/cherubicXN/afm_cvpr2019) |
| Sem-LSD | [Sem-LSD: A Learning-based Semantic Line Segment Detector](https://arxiv.org/abs/1909.06591v2) | arXiv 2019 | [[Code]](https://github.com/SunLoveSheep/Sem-LSD) |
 
## 1.2 Wireframe Parsing

| Name | Paper | Source | Resource |
| --- | --- | --- | --- |
| SOLD2 | [SOLD2: Self-supervised Occlusion-aware Line Description and Detection](https://ieeexplore.ieee.org/document/9578370) | CVPR 2021 | [[Code]](https://github.com/cvg/SOLD2) |
| ULSD | [ULSD: Unified Line Segment Detection across Pinhole, Fisheye, and Spherical Cameras](https://www.sciencedirect.com/science/article/pii/S0924271621001623) | ISPRS 2021 | [[Code]](https://github.com/lh9171338/ULSD-ISPRS) |
| HT-HAWP | [Deep Hough-Transform Line Priors](https://link.springer.com/chapter/10.1007/978-3-030-58542-6_20) | ECCV 2020 | [[Code]](https://github.com/yanconglin/Deep-Hough-Transform-Line-Priors) |
| HAWP | [Holistically-Attracted Wireframe Parsing](https://ieeexplore.ieee.org/document/9157705) | CVPR 2020 | [[Code]](https://github.com/cherubicXN/hawp) |
|  | [Learning to Reconstruct 3D Manhattan Wireframes from a Single Image](https://ieeexplore.ieee.org/document/9010693) | ICCV 2019 | [[Project]](https://yichaozhou.com/publication/1811learning/) |
|  | [Wireframe Parsing With Guidance of Distance Map](https://ieeexplore.ieee.org/document/8849984) | Access 2019 |  |
| L-CNN | [End-to-End Wireframe Parsing](https://ieeexplore.ieee.org/document/9008267) | ICCV 2019 | [[Code]](https://github.com/zhou13/lcnn) |
| DWP | [Learning to Parse Wireframes in Images of Man-Made Environments](https://ieeexplore.ieee.org/document/8578170) | CVPR 2018 | [[Code]](https://github.com/huangkuns/wireframe) |

---

# 2. Traditional Approaches

| Name | Paper | Source | Resource |
| --- | --- | --- | --- |
| PSLine | [Property Similarity Line Segment Detector](https://ieeexplore.ieee.org/document/9651397) | IST 2021 |  |
| ELSED | [ELSED: Enhanced Line SEgment Drawing](https://arxiv.org/abs/2108.03144) | arXiv 2021 | [[Code]](https://github.com/iago-suarez/ELSED) |
| PLSD | [PLSD: A Perceptually Accurate Line Segment Detection Approach](https://ieeexplore.ieee.org/document/9018038) | Access 2020 |  |
| MCMLSD | [MCMLSD: A Probabilistic Algorithm and Evaluation Framework for Line Segment Detection](https://arxiv.org/abs/2001.01788) | arXiv 2020 |  |
| Linelet | [A Novel Linelet-based Representation for Line Segment Detection](https://ieeexplore.ieee.org/document/7926451) | TPAMI 2017 | [[Code]](https://github.com/NamgyuCho/Linelet-code-and-YorkUrban-LineSegment-DB) |
| MCMLSD | [MCMLSD: A Dynamic Programming Approach to Line Segment Detection](https://ieeexplore.ieee.org/document/8100103) | CVPR 2017 | [[Code]](http://www.elderlab.yorku.ca/resources/) |
| CannyLines | [Cannylines: A parameter-free line segment detector](https://ieeexplore.ieee.org/document/7350850) | ICIP 2015 | [[Project]](https://cvrs.whu.edu.cn/cannylines/) |
|  | [Accurate and robust line segment extraction using minimum entropy with hough transform](https://ieeexplore.ieee.org/document/7000594) | TIP 2015 |  |
|  | [Lifting 3D manhattan lines from a single image](https://ieeexplore.ieee.org/document/6751171) | ICCV 2013 |  |
| LSD | [LSD: A Fast Line Segment Detector with a False Detection Control](https://ieeexplore.ieee.org/document/4731268) | TPAMI 2010 | [[Code]](http://www.ipol.im/pub/art/2012/gjmr-lsd/) |
| PPHT | [Robustdetection of lines using the progressive probabilistic hough transform](https://www.sciencedirect.com/science/article/pii/S1077314299908317) | CVIU 2000 |  |
|  | [Generalizing the hough transform to detect arbitrary shapes](https://www.sciencedirect.com/science/article/pii/0031320381900091) | PR 1981 |  |

---

# 3. Datasets

- [Wireframe Dataset](https://github.com/huangkuns/wireframe)
- [YorkUrbanDB (York Urban Line Segment Database)](http://www.elderlab.yorku.ca/resources/york-urban-line-segment-database-information/)
- [SS360 Dataset (spherical image dataset)](https://drive.google.com/drive/folders/1K-pGDDPrXkCmWCcoyYvURZ86ZzA5O6E_?usp=sharing)
