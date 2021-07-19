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

| Name | Paper | Source | Code/Project |
| --- | --- | --- | --- |
| ELSD | [ELSD: Efficient Line Segment Detector and Descriptor](https://arxiv.org/abs/2104.14205) | ArXiv 2021 |  |
| M-LSD | [Towards Real-time and Light-weight Line Segment Detection](https://arxiv.org/abs/2106.00186) | ArXiv 2021 | [[Code]](https://github.com/navervision/mlsd) |
| F-Clip | [Fully Convolutional Line Parsing](https://arxiv.org/abs/2104.11207v2) | ArXiv 2021 | [[Code]](https://github.com/Delay-Xili/F-Clip) |
| LETR | [Line Segment Detection Using Transformers without Edges](https://arxiv.org/abs/2101.01909) | CVPR 2021 | [[Code]](https://github.com/mlpc-ucsd/LETR) |
| TP-LSD | [TP-LSD: Tri-Points Based Line Segment Detector](https://arxiv.org/abs/2009.05505) | ECCV 2020 | [[Code]](https://github.com/MegviiRobot/TP-LSD) |
| LaRecNet | [Learning to Calibrate Straight Lines for Fisheye Image Rectification](http://openaccess.thecvf.com/content_CVPR_2019/papers/Xue_Learning_to_Calibrate_Straight_Lines_for_Fisheye_Image_Rectification_CVPR_2019_paper.pdf) | CVPR 2019 | [[Project]](https://xuezhucun.github.io/LaRecNet/) |
| PPGNet | [PPGNet: Learning Point-Pair Graph for Line Segment Detection](https://www.aiyoggle.me/publication/ppgnet-cvpr19/ppgnet-cvpr19.pdf) | CVPR 2019 | [[Code]](https://github.com/svip-lab/PPGNet) |
| AFM | [Learning Attraction Field Representation for Robust Line Segment Detection](https://arxiv.org/abs/1812.02122) | CVPR 2019 | [[Code]](https://github.com/cherubicXN/afm_cvpr2019) |
| Linelet | [A Novel Linelet-based Representation for Line Segment Detection.](https://ieeexplore.ieee.org/document/7926451) | TPAMI 2017 | [[Code]](https://github.com/NamgyuCho/Linelet-code-and-YorkUrban-LineSegment-DB) |
 
## 1.2 Wireframe Parsing

| Name | Paper | Source | Code/Project |
| --- | --- | --- | --- |
| HT-HAWP | [Deep Hough-Transform Line Priors](https://arxiv.org/abs/2007.09493) | ECCV 2020 | [[Code]](https://github.com/yanconglin/Deep-Hough-Transform-Line-Priors) |
| HAWP | [Holistically-Attracted Wireframe Parsing](https://arxiv.org/abs/2003.01663) | CVPR 2020 | [[Code]](https://github.com/cherubicXN/hawp) |
|  | [Learning to Reconstruct 3D Manhattan Wireframes from a Single Image](https://arxiv.org/abs/1905.07482) | ICCV 2019 | [[Project]](https://yichaozhou.com/publication/1811learning/) |
| L-CNN | [End-to-End Wireframe Parsing](https://arxiv.org/abs/1905.03246) | ICCV 2019 | [[Code]](https://github.com/zhou13/lcnn) |
| DWP | [Learning to Parse Wireframes in Images of Man-Made Environments](http://people.eecs.berkeley.edu/~yima/files/cvpr18-parsing-final.pdf) | CVPR 2018 | [[Code]](https://github.com/huangkuns/wireframe) |

---

# 2. Traditional Approaches

| Name | Paper | Source | Code/Project |
| --- | --- | --- | --- |
| MCMLSD | [MCMLSD: A Probabilistic Algorithm and Evaluation Framework for Line Segment Detection](https://arxiv.org/abs/2001.01788) | TPAMI 2020 |  |
| MCMLSD | [MCMLSD: A Dynamic Programming Approach to Line Segment Detection](http://www.elderlab.yorku.ca/wp-content/uploads/2016/12/Almazan_MCMLSD_A_Dynamic_CVPR_2017_paper.pdf) | CVPR 2017 | [[Code]](http://www.elderlab.yorku.ca/resources/) |
| CannyLines | [Cannylines: A parameter-free line segment detector](https://cvrs.whu.edu.cn/publications/2015/CannyLines-ICIP2015.pdf) | ICIP 2015 | [[Project]](https://cvrs.whu.edu.cn/cannylines/) |
|  | [Accurate and robust line segment extraction using minimum entropy with hough transform](https://ieeexplore.ieee.org/document/7000594) | TIP 2015 |  |
|  | [Lifting 3D manhattan lines from a single image](https://ieeexplore.ieee.org/document/6751171) | ICCV 2013 |  |
| LSD | [LSD: A Fast Line Segment Detector with a False Detection Control](https://ieeexplore.ieee.org/document/4731268) | TPAMI 2010 | [[Code]](http://www.ipol.im/pub/art/2012/gjmr-lsd/) |
| PPHT | [Robustdetection of lines using the progressive probabilistic hough transform]() | CVIU 2000 |  |
|  | [Generalizing the hough transform to detect arbitrary shapes](https://www.cs.bgu.ac.il/~icbv161/wiki.files/Readings/1981-Ballard-Generalizing_the_Hough_Transform_to_Detect_Arbitrary_Shapes.pdf) | PR 1981 |  |

---

# 3. Datasets

- [Wireframe Dataset](https://github.com/huangkuns/wireframe)
- [YorkUrbanDB (York Urban Line Segment Database)](http://www.elderlab.yorku.ca/resources/york-urban-line-segment-database-information/)
