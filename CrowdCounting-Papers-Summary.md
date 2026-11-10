# 人群计数（Crowd Counting）论文与代码汇总

> **内容**：人群计数领域 2008–2026 年论文的标题、下载链接，以及对应代码仓库链接（如有）
> **链接说明**：优先给出 arXiv / CVF Open Access / DOI 永久链接；少数未能检索到正式链接的论文给出 Google Scholar 检索链接
> **讲解资源**：第六部分收录了 Keep_Trying_Go 的 CSDN 博客详解与 Bilibili 视频讲解链接，并已内嵌到对应论文条目中
> **归类说明**：每篇论文仅列出一次，按年份/专题归类

---

## 目录

- [一、综述（Survey）](#一综述survey)
- [二、按年份分类论文（2012–2026）](#二按年份分类论文20122026)
- [三、其他经典论文](#三其他经典论文)
- [四、专题方向论文](#四专题方向论文)
- [五、代码仓库汇总](#五代码仓库汇总)
- [六、论文讲解博客与视频（Keep_Trying_Go）](#六论文讲解博客与视频keep_trying_go)

---

## 一、综述（Survey）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| A Survey on Deep Learning-based Single Image Crowd Counting: Network Design, Loss Function and Supervisory Signal | Neurocomputing 2022 | [arXiv:2012.15685](https://arxiv.org/abs/2012.15685) | - |
| A Survey of Recent Advances in CNN-based Single Image Crowd Counting and Density Estimation | Pattern Recognition Letters 2018 | [arXiv:1707.01202](https://arxiv.org/abs/1707.01202) | - |
| CNN-based Density Estimation and Crowd Counting: A Survey | ACM Computing Surveys 2020 | [arXiv:2003.12783](https://arxiv.org/abs/2003.12783) | - |

---

## 二、按年份分类论文（2012–2026）

### 2015 及更早

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Feature Mining for Localised Crowd Counting（mall 数据集） | BMVC 2012 | [PDF](https://pdfs.semanticscholar.org/c5ec/65e36bccf8a64050d38598511f0352653d6f.pdf) | - |
| Multi-Source Multi-Scale Counting in Extremely Dense Crowd Images（UCF_CC_50 数据集） | CVPR 2013 | [CVF](http://openaccess.thecvf.com/content_cvpr_2013/papers/Idrees_Multi-source_Multi-scale_Counting_2013_CVPR_paper.pdf) | - |

### 2016

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Single-Image Crowd Counting via Multi-Column Convolutional Neural Network（MCNN） | CVPR 2016 | [DOI:10.1109/CVPR.2016.70](https://doi.org/10.1109/CVPR.2016.70) | [PyTorch（非官方）](https://github.com/svishwa/crowdcount-mcnn) |
| CrowdNet: A Deep Convolutional Network for Dense Crowd Counting | ACM MM 2016 | [arXiv:1608.06197](https://arxiv.org/abs/1608.06197) | [非官方](https://github.com/davideverona/deep-crowd-counting_crowdnet) |
| Domain-Adversarial Training of Neural Networks（DANN） | JMLR 2016 | [JMLR](http://jmlr.org/papers/v17/15-239.html) | - |

### 2017

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Fully Convolutional Crowd Counting On Highly Congested Scenes（FCNCC） | VISAPP 2017 | [arXiv:1612.00220](https://arxiv.org/abs/1612.00220) | - |
| Switching Convolutional Neural Network for Crowd Counting（Switching-CNN） | CVPR 2017 | [DOI:10.1109/CVPR.2017.429](https://doi.org/10.1109/CVPR.2017.429) / [arXiv:1708.00199](https://arxiv.org/abs/1708.00199) | [官方](https://github.com/val-iisc/crowd-counting-scnn) |
| Generating High-Quality Crowd Density Maps using Contextual Pyramid CNNs（CP-CNN） | ICCV 2017 | [arXiv:1708.00953](https://arxiv.org/abs/1708.00953) | - |
| CNN-based Cascaded Multi-task Learning of High-level Prior and Density Estimation for Crowd Counting（CMTL） | AVSS 2017 | [DOI:10.1109/AVSS.2017.8078491](https://doi.org/10.1109/AVSS.2017.8078491) | [官方](https://github.com/svishwa/crowdcount-cascaded-mtl) |
| Image Crowd Counting Using Convolutional Neural Network and Markov Random Field（CNN-MRF） | JACIII 2017 | [arXiv:1706.03686](https://arxiv.org/abs/1706.03686) | [官方](https://github.com/hankong/crowd-counting) |
| Multi-scale Convolution Neural Networks for Crowd Counting（MSCNN） | ICIP 2017 | [arXiv:1702.02359](https://arxiv.org/abs/1702.02359) | [官方](https://github.com/Ling-Bao/mscnn) |
| ResnetCrowd: A Residual Deep Learning Architecture for Crowd Counting, Violent Behaviour Detection and Crowd Density Level Classification | AVSS 2017 | [arXiv:1705.10698](https://arxiv.org/abs/1705.10698) | - |

### 2018

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| A Deeply-Recursive Convolutional Network for Crowd Counting（DR-ResNet） | ICASSP 2018 | [arXiv:1805.05633](https://arxiv.org/abs/1805.05633) | - |
| Crowd Counting via Adversarial Cross-Scale Consistency Pursuit（ACSCP） | CVPR 2018 | [CVF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Shen_Crowd_Counting_via_CVPR_2018_paper.pdf) | [PyTorch（非官方）](https://github.com/RQuispeC/pytorch-ACSCP) |
| ADCrowdNet: An Attention-injective Deformable Convolutional Network for Crowd Understanding | CVPR 2019 | [DOI:10.1109/CVPR.2019.00334](https://doi.org/10.1109/CVPR.2019.00334) / [arXiv:1811.11968](https://arxiv.org/abs/1811.11968) | - |
| Autoencoding beyond pixels using a learned similarity metric（VAE） | ICLR 2016 | [arXiv:1512.09300](https://arxiv.org/abs/1512.09300) | - |
| Crowd counting via scale-adaptive convolutional neural network（SaCNN） | WACV 2018 | [DOI:10.1109/WACV.2018.00127](https://doi.org/10.1109/WACV.2018.00127) | [官方](https://github.com/miao0913/SaCNN-CrowdCounting-Tencent_Youtu) |
| Crowd Counting with Deep Negative Correlation Learning（D-ConvNet） | CVPR 2018 | [DOI:10.1109/CVPR.2018.00564](https://doi.org/10.1109/CVPR.2018.00564) / [CVF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Shi_Crowd_Counting_With_CVPR_2018_paper.pdf) | [官方](https://github.com/shizenglin/Deep-NCL) |
| Crowd Counting by Adaptively Fusing Predictions from an Image Pyramid（AFP） | BMVC 2018 | [arXiv:1805.06115](https://arxiv.org/abs/1805.06115) | - |
| Class-Agnostic Counting（GMN） | ACCV 2018 | [arXiv:1811.00472](https://arxiv.org/abs/1811.00472) | [官方](https://github.com/erikalu/class-agnostic-counting) |
| In Defense of Single-column Networks for Crowd Counting（SCNet） | BMVC 2018 | [arXiv:1808.06133](https://arxiv.org/abs/1808.06133) | - |
| Two at Once: Enhancing Learning and Generalization Capacities via IBN-Net | ECCV 2018 | [DOI:10.1007/978-3-030-01225-0_29](https://doi.org/10.1007/978-3-030-01225-0_29) / [arXiv:1807.09441](https://arxiv.org/abs/1807.09441) | [官方](https://github.com/XingangPan/IBN-Net) |

### 2019

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Adaptive Scenario Discovery for Crowd Counting（ASD） | ICASSP 2019 | [arXiv:1812.02393](https://arxiv.org/abs/1812.02393) | - |
| Adaptive Dilated Network with Self-Correction Supervision for Counting（ADSCNet） | CVPR 2020 | [DOI:10.1109/CVPR42600.2020.00465](https://doi.org/10.1109/CVPR42600.2020.00465) / [CVF](http://openaccess.thecvf.com/content_CVPR_2020/papers/Bai_Adaptive_Dilated_Network_With_Self-Correction_Supervision_for_Counting_CVPR_2020_paper.pdf) | - |
| Bayesian Loss for Crowd Count Estimation with Point Supervision（BL） | ICCV 2019 (Oral) | [DOI:10.1109/ICCV.2019.00624](https://doi.org/10.1109/ICCV.2019.00624) / [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Ma_Bayesian_Loss_for_Crowd_Count_Estimation_With_Point_Supervision_ICCV_2019_paper.pdf) | [官方](https://github.com/ZhihengCV/Bayesian-Crowd-Counting) |
| C^3 Framework: An Open-source PyTorch Code for Crowd Counting | arXiv 2019 | [arXiv:1907.02724](https://arxiv.org/abs/1907.02724) | [官方](https://github.com/gjy3035/C-3-Framework) |
| CSRNet: Dilated Convolutional Neural Networks for Understanding the Highly Congested Scenes | CVPR 2018 | [arXiv:1802.10062](https://arxiv.org/abs/1802.10062) | [PyTorch（非官方）](https://github.com/leeyeehoo/CSRNet-pytorch) |
| DecideNet: Counting Varying Density Crowds Through Attention Guided Detection and Density Estimation | CVPR 2018 | [arXiv:1712.06679](https://arxiv.org/abs/1712.06679) | - |
| Dense Scale Network for Crowd Counting（DSNet） | ICMR 2019 | [arXiv:1906.09707](https://arxiv.org/abs/1906.09707) | [PyTorch（非官方）](https://github.com/rongliangzi/Dense-Scale-Network-for-Crowd-Counting) |
| Crowd Counting with Deep Structured Scale Integration Network（DSSINet） | ICCV 2019 | [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Liu_Crowd_Counting_With_Deep_Structured_Scale_Integration_Network_ICCV_2019_paper.pdf) | [官方](https://github.com/Legion56/Counting-ICCV-DSSINet) |
| Dual Path Multi-Scale Fusion Networks with Attention for Crowd Counting（SFANet） | ICASSP 2019 | [arXiv:1902.01115](https://arxiv.org/abs/1902.01115) | - |
| f-VAEGAN-D2: A Feature Generating Framework for Any-Shot Learning | CVPR 2019 | [DOI:10.1109/CVPR.2019.01052](https://doi.org/10.1109/CVPR.2019.01052) / [arXiv:1903.10160](https://arxiv.org/abs/1903.10160) | - |
| HA-CCN: Hierarchical Attention-based Crowd Counting Network | TIP 2020 | [DOI:10.1109/TIP.2019.2928634](https://doi.org/10.1109/TIP.2019.2928634) / [arXiv:1907.10255](https://arxiv.org/abs/1907.10255) | - |
| Improving Object Counting with Heatmap Regulation | CVPRW 2019 | [arXiv:1803.05494](https://arxiv.org/abs/1803.05494) | [官方](https://github.com/littleaich/heatmap-regulation) |
| Learning from Synthetic Data for Crowd Counting in the Wild（GCC / SFCN） | CVPR 2019 | [DOI:10.1109/CVPR.2019.00839](https://doi.org/10.1109/CVPR.2019.00839) / [arXiv:1903.03303](https://arxiv.org/abs/1903.03303) | [官方（GCC-CL）](https://github.com/gjy3035/GCC-CL) |
| Leveraging Unlabeled Data for Crowd Counting by Learning to Rank（L2R） | CVPR 2018 | [DOI:10.1109/CVPR.2018.00799](https://doi.org/10.1109/CVPR.2018.00799) / [arXiv:1803.03095](https://arxiv.org/abs/1803.03095) | [官方](https://github.com/xialeiliu/CrowdCountingCVPR18) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/154913403) |
| Recurrent Attentive Zooming for Joint Crowd Counting and Precise Localization（RAZ-Net） | CVPR 2019 | [PDF](http://www.muyadong.com/paper/cvpr19_0484.pdf) | - |
| Multi-Level Bottom-Top and Top-Bottom Feature Fusion for Crowd Counting（MBTTBF） | ICCV 2019 | [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Sindagi_Multi-Level_Bottom-Top_and_Top-Bottom_Feature_Fusion_for_Crowd_Counting_ICCV_2019_paper.pdf) | - |
| MRCNet: Crowd Counting and Density Map Estimation in Aerial and Ground Imagery | BMVCW 2019 | [arXiv:1909.12743](https://arxiv.org/abs/1909.12743) | - |
| Improving Dense Crowd Counting Convolutional Neural Networks using Inverse k-Nearest Neighbor Maps and Multiscale Upsampling（ikNN） | VISAPP 2019 | [arXiv:1902.05379](https://arxiv.org/abs/1902.05379) | - |
| Revisiting Perspective Information for Efficient Crowd Counting（PACNN + R-ASPP） | CVPR 2019 | [DOI:10.1109/CVPR.2019.00745](https://doi.org/10.1109/CVPR.2019.00745) / [arXiv:1807.01989](https://arxiv.org/abs/1807.01989v3) | - |
| PCC Net: Perspective Crowd Counting via Spatial Convolutional Network | T-CSVT 2019 | [arXiv:1905.10085](https://arxiv.org/abs/1905.10085) | [官方](https://github.com/gjy3035/PCC-Net) |
| Perspective-Guided Convolution Networks for Crowd Counting（PGCNet） | ICCV 2019 | [DOI:10.1109/ICCV.2019.00104](https://doi.org/10.1109/ICCV.2019.00104) / [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Perspective-Guided_Convolution_Networks_for_Crowd_Counting_ICCV_2019_paper.pdf) | [官方](https://github.com/Zhaoyi-Yan/PGCNet) |
| Pushing the Frontiers of Unconstrained Crowd Counting: New Dataset and Benchmark Method（CG-DRCN，JHU-Crowd） | ICCV 2019 | [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Sindagi_Pushing_the_Frontiers_of_Unconstrained_Crowd_Counting_New_Dataset_and_ICCV_2019_paper.pdf) | - |
| Relational Attention Network for Crowd Counting（RANet） | ICCV 2019 | [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Relational_Attention_Network_for_Crowd_Counting_ICCV_2019_paper.pdf) | - |
| From Open Set to Closed Set: Counting Objects by Spatial Divide-and-Conquer（S-DCNet） | ICCV 2019 | [DOI:10.1109/ICCV.2019.00845](https://doi.org/10.1109/ICCV.2019.00845) / [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Xiong_From_Open_Set_to_Closed_Set_Counting_Objects_by_Spatial_ICCV_2019_paper.pdf) | [官方](https://github.com/xhp-hust-2018-2011/S-DCNet) |
| Crowd Counting on Images with Scale Variation and Isolated Clusters（SACANet） | ICCVW 2019 | [DOI:10.1109/ICCVW.2019.00009](https://doi.org/10.1109/ICCVW.2019.00009) / [arXiv:1909.03839](https://arxiv.org/abs/1909.03839) | - |
| Scale Aggregation Network for Accurate and Efficient Crowd Counting（SANet） | ECCV 2018 | [CVF](http://openaccess.thecvf.com/content_ECCV_2018/papers/Xinkun_Cao_Scale_Aggregation_Network_ECCV_2018_paper.pdf) | - |
| Point in, Box out: Beyond Counting Persons in Crowds（PSDDN / SDNet） | CVPR 2019 (Oral) | [arXiv:1904.01333](https://arxiv.org/abs/1904.01333) | - |
| Learning Spatial Awareness to Improve Crowd Counting（SPANet） | ICCV 2019 (Oral) | [DOI:10.1109/ICCV.2019.00625](https://doi.org/10.1109/ICCV.2019.00625) / [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Cheng_Learning_Spatial_Awareness_to_Improve_Crowd_Counting_ICCV_2019_paper.pdf) | - |
| Scale Pyramid Network for Crowd Counting（SPN） | WACV 2019 | [Scholar](https://scholar.google.com/scholar?q=Scale+Pyramid+Network+for+Crowd+Counting) | - |
| Stacked Pooling: Improving Crowd Counting by Boosting Scale Invariance | ICASSP 2020 | [arXiv:1808.07456](https://arxiv.org/abs/1808.07456) | [官方](https://github.com/siyuhuang/crowdcount-stackpool) |

### 2020

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Adaptive Mixture Regression Network with Local Counting Map for Crowd Counting（AMRNet） | ECCV 2020 | [DOI:10.1007/978-3-030-58586-0_15](https://doi.org/10.1007/978-3-030-58586-0_15) / [arXiv:2005.05776](https://arxiv.org/abs/2005.05776) | [官方](https://github.com/xiyang1012/Local-Crowd-Counting) |
| Ambient Sound Helps: Audiovisual Crowd Counting in Extreme Conditions | ACM MM 2020 | [arXiv:2005.07097](https://arxiv.org/abs/2005.07097) | [官方](https://github.com/qingzwang/AudioVisualCrowdCounting) |
| Completely Self-Supervised Crowd Counting via Distribution Matching（CSS-CCNN） | TIP 2022 | [arXiv:2009.06420](https://arxiv.org/abs/2009.06420) | [官方](https://github.com/val-iisc/css-ccnn) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/148147162) |
| Deep Density-aware Count Regressor（DeepCount） | ECAI 2020 | [arXiv:1908.03314](https://arxiv.org/abs/1908.03314) | [官方](https://github.com/GeorgeChenZJ/deepcount) |
| Distribution Matching for Crowd Counting（DM-Count） | NeurIPS 2020 | [arXiv:2009.13077](https://arxiv.org/abs/2009.13077) | [官方](https://github.com/cvlab-stonybrook/DM-Count) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/143133438) / [损失函数详解](https://blog.csdn.net/Keep_Trying_Go/article/details/143219789) |
| Encoder-Decoder Based Convolutional Neural Networks with Multi-Scale-Aware Modules for Crowd Counting（M-SFANet / M-SegNet） | ICPR 2020 | [DOI:10.1109/ICPR48806.2021.9413286](https://doi.org/10.1109/ICPR48806.2021.9413286) / [arXiv:2003.05586](https://arxiv.org/abs/2003.05586) | [官方](https://github.com/Pongpisit-Thanasutives/Variations-of-SFANet-for-Crowd-Counting) |
| Estimating People Flows to Better Count Them in Crowded Scenes（EPF） | ECCV 2020 | [DOI:10.1007/978-3-030-58555-6_43](https://doi.org/10.1007/978-3-030-58555-6_43) / [arXiv:1911.10782](https://arxiv.org/abs/1911.10782) | [官方](https://github.com/weizheliu/People-Flows) |
| Exploit the Potential of Multi-column Architecture for Crowd Counting（PSNet） | arXiv 2020 | [arXiv:2007.05779](https://arxiv.org/abs/2007.05779) | [官方](https://github.com/JunhaoCheng/Pyramid_Scale_Network) |
| Interlayer and Intralayer Scale Aggregation for Scale-invariant Crowd Counting（ScSiNet） | Neurocomputing 2020 | [DOI:10.1016/j.neucom.2021.01.112](https://doi.org/10.1016/j.neucom.2021.01.112) / [arXiv:2005.11943](https://arxiv.org/abs/2005.11943) | - |
| JHU-CROWD++: Large-Scale Crowd Counting Dataset and A Benchmark Method | TPAMI 2020 | [DOI:10.1109/TPAMI.2020.3035969](https://doi.org/10.1109/TPAMI.2020.3035969) / [arXiv:2004.03597](https://arxiv.org/abs/2004.03597) | - |
| Localization in the Crowd with Topological Constraints（TopoCount） | AAAI 2020 | [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/16170) | [官方](https://github.com/ShahiraAbousamra/TopoCount) |
| Locate, Size and Count: Accurately Resolving People in Dense Crowds via Detection（LSC-CNN） | TPAMI 2021 | [arXiv:1906.07538](https://arxiv.org/abs/1906.07538) | [官方](https://github.com/val-iisc/lsc-cnn) |
| Multi-Stream Networks and Ground-Truth Generation for Crowd Counting | arXiv 2020 | [arXiv:2002.09951](https://arxiv.org/abs/2002.09951) | - |
| NWPU-Crowd: A Large-Scale Benchmark for Crowd Counting and Localization | TPAMI 2020 | [DOI:10.1109/TPAMI.2020.3013269](https://doi.org/10.1109/TPAMI.2020.3013269) / [arXiv:2001.03360](https://arxiv.org/abs/2001.03360) | [官方](https://github.com/gjy3035/NWPU-Crowd-Sample-Code) |
| Pixel-wise Crowd Understanding via Synthetic Data（GCC 数据集） | IJCV 2021 | [arXiv:2007.16032](https://arxiv.org/abs/2007.16032) | [官方（GCC-SFCN）](https://github.com/gjy3035/GCC-SFCN) |
| Residual Regression with Semantic Prior for Crowd Counting（RRSP） | CVPR 2019 | [CVF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wan_Residual_Regression_With_Semantic_Prior_for_Crowd_Counting_CVPR_2019_paper.pdf) | [官方](https://github.com/jia-wan/ResidualRegression-pytorch) |
| Crowd Counting via Segmentation Guided Attention Networks and Curriculum Loss（SGANet） | T-ITS 2022 | [DOI:10.1109/TITS.2021.3138896](https://doi.org/10.1109/TITS.2021.3138896) | - |
| Towards Unsupervised Crowd Counting via Regression-Detection Bi-knowledge Transfer（RDBT） | ACM MM 2020 | [arXiv:2008.05383](https://arxiv.org/abs/2008.05383) | - |
| Uncertainty Estimation and Sample Selection for Crowd Counting（CTN） | ACCV 2020 | [DOI:10.1007/978-3-030-69541-5_23](https://doi.org/10.1007/978-3-030-69541-5_23) / [arXiv:2009.14411](https://arxiv.org/abs/2009.14411) | - |
| Weighing Counts: Sequential Crowd Counting by Reinforcement Learning（LibraNet） | ECCV 2020 | [DOI:10.1007/978-3-030-58607-2_10](https://doi.org/10.1007/978-3-030-58607-2_10) / [arXiv:2007.08260](https://arxiv.org/abs/2007.08260) | [官方](https://github.com/poppinace/libranet) |
| VisDrone-CC2020: The Vision Meets Drone Crowd Counting Challenge Results | ECCVW 2020 | [arXiv:2107.08766](https://arxiv.org/abs/2107.08766) | - |

### 2021

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| A Self-Training Approach for Point-Supervised Object Detection and Counting in Crowds（PSODNet） | TIP 2021 | [DOI:10.1109/TIP.2021.3055632](https://doi.org/10.1109/TIP.2021.3055632) / [arXiv:2007.12831](https://arxiv.org/abs/2007.12831) | [官方](https://github.com/WangyiNTU/Point-supervised-crowd-detection) |
| Multi-Scale Context Aggregation Network with Attention-Guided for Crowd Counting（MSCANet） | ICSP 2020 | [DOI:10.1109/ICSP48669.2020.9321067](https://doi.org/10.1109/ICSP48669.2020.9321067) | - |
| AutoScale: Learning to Scale for Crowd Counting | IJCV 2022 | [DOI:10.1007/s11263-021-01542-z](https://doi.org/10.1007/s11263-021-01542-z) | [官方](https://github.com/dk-liang/AutoScale) |
| CCTrans: Simplifying and Improving Crowd Counting with Transformer | arXiv 2021 | [arXiv:2109.14483](https://arxiv.org/abs/2109.14483) | - |
| Coarse- and Fine-grained Attention Network with Background-aware Loss for Crowd Density Map Estimation（CFANet / MARUNet） | WACV 2021 | [arXiv:2011.03721](https://arxiv.org/abs/2011.03721) | [官方](https://github.com/rongliangzi/MARUNet) |
| Congested Crowd Instance Localization with Dilated Convolutional Swin Transformer（DCST） | Neurocomputing 2022 | [arXiv:2108.00584](https://arxiv.org/abs/2108.00584) | - |
| Cross-Modal Collaborative Representation Learning and a Large-Scale RGBT Benchmark for Crowd Counting（RGBT-CC 数据集） | CVPR 2021 | [arXiv:2012.04529](https://arxiv.org/abs/2012.04529) / [CVF](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Cross-Modal_Collaborative_Representation_Learning_and_a_Large-Scale_RGBT_Benchmark_for_CVPR_2021_paper.pdf) | [官方](https://github.com/chen-judge/RGBTCrowdCounting) |
| Masksembles for Uncertainty Estimation | ICLR 2021 | [arXiv:2012.08334](https://arxiv.org/abs/2012.08334) | [官方](https://github.com/nikitadurasov/masksembles) |
| Rethinking Counting and Localization in Crowds: A Purely Point-Based Framework（P2PNet） | ICCV 2021 (Oral) | [arXiv:2107.12746](https://arxiv.org/abs/2107.12746) | [官方](https://github.com/TencentYoutuResearch/CrowdCounting-P2PNet) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/154443638) |
| Crowd Counting via Perspective-Guided Fractional-Dilation Convolution（PFDNet） | TMM 2022 | [DOI:10.1109/TMM.2021.3086709](https://doi.org/10.1109/TMM.2021.3086709) | - |
| To Choose or to Fuse? Scale Selection for Crowd Counting（SASNet） | AAAI 2021 | [DOI:10.1609/aaai.v35i3.16360](https://doi.org/10.1609/aaai.v35i3.16360) | [官方](https://github.com/TencentYoutuResearch/CrowdCounting-SASNet) |
| Dense Point Prediction: A Simple Baseline for Crowd Counting and Localization（SCALNet） | ICMEW 2021 | [arXiv:2104.12505](https://arxiv.org/abs/2104.12505) | [官方](https://github.com/WangyiNTU/SCALNet) |
| Segmentation Assisted U-shaped Multi-scale Transformer for Crowd Counting（CUT） | BMVC 2022 | [ResearchGate](https://www.researchgate.net/publication/364030579_Segmentation_Assisted_U-shaped_Multi-scale_Transformer_for_Crowd_Counting) | - |
| Uniformity in Heterogeneity: Diving Deep into Count Interval Partition for Crowd Counting（UEPNet） | ICCV 2021 | [DOI:10.1109/ICCV48922.2021.00322](https://doi.org/10.1109/ICCV48922.2021.00322) / [arXiv:2107.12619](https://arxiv.org/abs/2107.12619) | [官方](https://github.com/TencentYoutuResearch/CrowdCounting-UEPNet) |

### 2022

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Semi-supervised Crowd Counting via Density Agency（DACount） | ACM MM 2022 | [arXiv:2209.02955](https://arxiv.org/abs/2209.02955) | [官方](https://github.com/LoraLinH/Semi-supervised-Crowd-Counting-via-Density-Agency) |
| An Improved Normed-Deformable Convolution for Crowd Counting（NDAConv） | IEEE SPL 2022 | [arXiv:2206.08084](https://arxiv.org/abs/2206.08084) | - |
| Analysis of the Effect of Low-Overhead Lossy Image Compression on the Performance of Visual Crowd Counting for Smart City Applications | arXiv 2022 | [arXiv:2207.10155](https://arxiv.org/abs/2207.10155) | - |
| Crowd Counting with Crowd Attention Convolutional Neural Network（CCANet / CAT-CNN） | Neurocomputing 2020 | [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0925231219316662) | - |
| CrowdFormer: An Overlap Patching Vision Transformer for Top-Down Crowd Counting | IJCAI 2022 | [DOI:10.24963/ijcai.2022/215](https://doi.org/10.24963/ijcai.2022/215) | - |
| ECCNAS: Efficient Crowd Counting Neural Architecture Search | ACM TOMM 2022 | [DOI:10.1145/3465455](https://doi.org/10.1145/3465455) | - |
| Learning Independent Instance Maps for Crowd Localization（IIM） | TPAMI 2022 | [arXiv:2012.04164](https://arxiv.org/abs/2012.04164) | [官方](https://github.com/taohan10200/IIM) |
| Improving Local Features with Relevant Spatial Information by Vision Transformer for Crowd Counting（LoViTCrowd） | BMVC 2022 | [PDF](https://bmvc2022.mpi-inf.mpg.de/0729.pdf) | [官方](https://github.com/nguyen1312/LoViTCrowd) |
| Inception-Based Crowd Counting — Being Fast while Remaining Accurate（ICCNet） | arXiv 2022 | [arXiv:2210.09796](https://arxiv.org/abs/2210.09796) | - |
| Joint CNN and Transformer Network via Weakly Supervised Learning for Efficient Crowd Counting | arXiv 2022 | [arXiv:2203.06388](https://arxiv.org/abs/2203.06388) | - |
| Multiscale Crowd Counting and Localization by Multitask Point Supervision（MPS） | ICASSP 2022 | [DOI:10.1109/ICASSP43922.2022.9747776](https://doi.org/10.1109/ICASSP43922.2022.9747776) / [arXiv:2202.09942](https://arxiv.org/abs/2202.09942) | [官方](https://github.com/RCVLab-AiimLab/crowd_counting) |
| Omni-Dimensional Dynamic Convolution（ODConv） | ICLR 2022 | [arXiv:2209.07147](https://arxiv.org/abs/2209.07147) | - |
| PSGCNet: A Pyramidal Scale and Global Context Guided Network for Dense Object Counting in Remote Sensing Images | TGRS 2022 | [IEEE](https://ieeexplore.ieee.org/document/9720990) | [官方](https://github.com/gaoguangshuai/psgcnet) |
| TAFNet: A Three-Stream Adaptive Fusion Network for RGB-T Crowd Counting | ISCAS 2022 | [arXiv:2202.08517](https://arxiv.org/abs/2202.08517) | [官方](https://github.com/TANGHAIHAN/TAFNet) |
| TransCrowd: Weakly-Supervised Crowd Counting with Transformer | Science China Information Sciences 2022 | [DOI:10.1007/s11432-021-3445-y](https://doi.org/10.1007/s11432-021-3445-y) / [arXiv:2104.09116](https://arxiv.org/abs/2104.09116) | [官方](https://github.com/dk-liang/TransCrowd) |

### 2023

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Application of Improved Transformer Based on Weakly Supervised in Crowd Localization and Crowd Counting | Scientific Reports 2023 | [DOI:10.1038/s41598-022-27299-0](https://doi.org/10.1038/s41598-022-27299-0) | - |
| Counting Manatee Aggregations using Deep Neural Networks and Anisotropic Gaussian Kernel | Scientific Reports 2023 | [DOI:10.1038/s41598-023-45507-3](https://doi.org/10.1038/s41598-023-45507-3) | [官方](https://github.com/yeyimilk/deep-learning-for-manatee-counting) |
| Cross-Head Supervision for Crowd Counting with Noisy Annotations（CHS-Net） | ICASSP 2023 | [DOI:10.1109/ICASSP49357.2023.10095636](https://doi.org/10.1109/ICASSP49357.2023.10095636) / [arXiv:2303.09245](https://arxiv.org/abs/2303.09245) | [官方](https://github.com/RaccoonDML/CHSNet) |
| Boosting Detection in Crowd Analysis via Underutilized Output Features（Crowd-Hat） | CVPR 2023 | [DOI:10.1109/CVPR52729.2023.01498](https://doi.org/10.1109/CVPR52729.2023.01498) / [CVF](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_Boosting_Detection_in_Crowd_Analysis_via_Underutilized_Output_Features_CVPR_2023_paper.pdf) | [官方](https://github.com/wskingdom/Crowd-Hat) |
| CrowdFormer: Weakly-Supervised Crowd Counting with Improved Generalizability（Savner & Kanhangad） | arXiv 2022 | [arXiv:2203.03768](https://arxiv.org/abs/2203.03768) | - |
| DAOT: Domain-Agnostically Aligned Optimal Transport for Domain-Adaptive Crowd Counting | ACM MM 2023 | [arXiv:2308.05311](https://arxiv.org/abs/2308.05311) | - |
| Domain-general Crowd Counting in Unseen Scenarios（DCCUS） | AAAI 2023 | [arXiv:2212.02573](https://arxiv.org/abs/2212.02573) | [官方](https://github.com/ZPDu/Domain-general-Crowd-Counting-in-Unseen-Scenarios) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/142730047) |
| Diffuse-Denoise-Count: Accurate Crowd-Counting with Diffusion Models（DDC） | CVPRW 2023 | [arXiv:2303.12790](https://arxiv.org/abs/2303.12790) | [官方](https://github.com/dylran/DiffuseDenoiseCount) |
| Deep Rank-Consistent Pyramid Model for Enhanced Crowd Counting（DREAM / DREAMNet） | TNNLS 2023 | [DOI:10.1109/TNNLS.2023.3336774](https://doi.org/10.1109/TNNLS.2023.3336774) / [arXiv:2201.04819](https://arxiv.org/abs/2201.04819) | - |
| Run, Don't Walk: Chasing Higher FLOPS for Faster Neural Networks（FasterNeXt） | CVPR 2023 | [DOI:10.1109/CVPR52729.2023.01157](https://doi.org/10.1109/CVPR52729.2023.01157) | - |
| Improving Deep Regression with Ordinal Entropy | ICLR 2023 | [arXiv:2301.08915](https://arxiv.org/abs/2301.08915) | - |
| A Low-Shot Object Counting Network with Iterative Prototype Adaptation（LOCA） | ICCV 2023 | [DOI:10.1109/ICCV51070.2023.01730](https://doi.org/10.1109/ICCV51070.2023.01730) | - |
| Super-Resolution Information Enhancement for Crowd Counting（MSSRM） | ICASSP 2023 | [arXiv:2303.06925](https://arxiv.org/abs/2303.06925) | [官方](https://github.com/PRIS-CV/MSSRM) |
| Rethinking Global Context in Crowd Counting | Machine Intelligence Research 2024 | [DOI:10.1007/s11633-023-1475-z](https://doi.org/10.1007/s11633-023-1475-z) | - |
| Redesigning Multi-Scale Neural Network for Crowd Counting（HMoDE / RMSN） | TIP 2023 | [DOI:10.1109/TIP.2023.3289290](https://doi.org/10.1109/TIP.2023.3289290) / [arXiv:2208.02894](https://arxiv.org/abs/2208.02894) | [官方](https://github.com/ZPDu/Redesigning-Multi-Scale-Neural-Network-for-Crowd-Counting) |
| SimMIM: A Simple Framework for Masked Image Modeling | CVPR 2022 | [arXiv:2111.09886](https://arxiv.org/abs/2111.09886) | [官方](https://github.com/microsoft/SimMIM) |
| STEERER: Resolving Scale Variations for Counting and Localization via Selective Inheritance Learning | ICCV 2023 | [arXiv:2308.10468](https://arxiv.org/abs/2308.10468) | [官方](https://github.com/taohan10200/STEERER) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/154789450) |
| CrowdCLIP: Unsupervised Crowd Counting via Vision-Language Model | CVPR 2023 | [arXiv:2304.04231](https://arxiv.org/abs/2304.04231) | [官方](https://github.com/dk-liang/CrowdCLIP) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/147851355) |

### 2024

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Accurate Gigapixel Crowd Counting by Iterative Zooming and Refinement | arXiv 2023 | [arXiv:2305.09271](https://arxiv.org/abs/2305.09271) | - |
| CLIP-EBC: CLIP Can Count Accurately through Enhanced Blockwise Classification | ICME 2025 / arXiv 2024 | [DOI:10.1109/ICME59968.2025.11209839](https://doi.org/10.1109/ICME59968.2025.11209839) / [arXiv:2403.09281](https://arxiv.org/abs/2403.09281) | [官方](https://github.com/Yiming-M/CLIP-EBC) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/147819012) |
| Crowd-SAM: SAM as a Smart Annotator for Object Detection in Crowded Scenes | ECCV 2024 | [arXiv:2407.11464](https://arxiv.org/abs/2407.11464) | [官方](https://github.com/FelixCaae/CrowdSAM) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/168236939) |
| CrowdDiff: Multi-Hypothesis Crowd Density Estimation using Diffusion Models | CVPR 2024 | [DOI:10.1109/CVPR52733.2024.01217](https://doi.org/10.1109/CVPR52733.2024.01217) / [CVF](https://openaccess.thecvf.com/content/CVPR2024/papers/Ranasinghe_CrowdDiff_Multi-hypothesis_Crowd_Density_Estimation_using_Diffusion_Models_CVPR_2024_paper.pdf) | [官方](https://github.com/dylran/crowddiff) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/157175412) |
| Diffusion-based Data Augmentation for Object Counting Problems | arXiv 2024 | [arXiv:2401.13992](https://arxiv.org/abs/2401.13992) | - |
| Gramformer: Learning Crowd Counting via Graph-Modulated Transformer | AAAI 2024 | [DOI:10.1609/aaai.v38i4.28126](https://doi.org/10.1609/aaai.v38i4.28126) / [arXiv:2401.03870](https://arxiv.org/abs/2401.03870) | [官方](https://github.com/LoraLinH/Gramformer) |
| Mask Focal Loss: A Unifying Framework for Dense Crowd Counting with Canonical Object Detection Networks | arXiv 2022 | [arXiv:2212.11542](https://arxiv.org/abs/2212.11542) | - |
| Single Domain Generalization for Crowd Counting（MPCount） | CVPR 2024 | [arXiv:2403.09124](https://arxiv.org/abs/2403.09124) | [官方](https://github.com/Shimmer93/MPCount) |
| Multi-modal Crowd Counting via a Broker Modality（BM） | ECCV 2024 | [arXiv:2407.07518](https://arxiv.org/abs/2407.07518) | [官方](https://github.com/HenryCilence/Broker-Modality-Crowd-Counting) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/156830311) |
| Regressor-Segmenter Mutual Prompt Learning for Crowd Counting（mPrompt） | CVPR 2024 | [arXiv:2312.01711](https://arxiv.org/abs/2312.01711) | - |
| Robust Zero-Shot Crowd Counting and Localization with Adaptive Resolution SAM | ECCV 2024 | [arXiv:2402.17514](https://arxiv.org/abs/2402.17514) | [官方](https://github.com/jia-wan/AdaSEEMCount_pytorch) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/148300284) |
| StochCA: A Novel Approach for Exploiting Pretrained Models with Cross-Attention | Neural Networks 2024 | [DOI:10.1016/j.neunet.2024.106663](https://doi.org/10.1016/j.neunet.2024.106663) | - |
| Towards Automatic Power Battery Detection: New Challenge, Benchmark Dataset and Baseline | CVPR 2024 | [DOI:10.1109/CVPR52733.2024.02079](https://doi.org/10.1109/CVPR52733.2024.02079) / [arXiv:2312.02528](https://arxiv.org/abs/2312.02528) | - |
| Virtual Classification: Modulating Domain-Specific Knowledge for Multidomain Crowd Counting（MDKNet） | TNNLS 2025 | [DOI:10.1109/TNNLS.2024.3350363](https://doi.org/10.1109/TNNLS.2024.3350363) | [官方](https://github.com/csguomy/MDKNet) |

### 2025

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| A Novel Multi-Data-Augmentation and Multi-Deep-Learning Framework for Counting Small Vehicles and Crowds | IJPRAI 2024 | [DOI:10.1142/S0218001424520013](https://doi.org/10.1142/S0218001424520013) | - |
| A Crowd Counting and Localization Network Based on Adaptive Feature Fusion and Multi-Scale Global Attention Up Sampling | IEEE Access 2024 | [DOI:10.1109/ACCESS.2024.3356604](https://doi.org/10.1109/ACCESS.2024.3356604) | - |
| Counting Crowds in Bad Weather（AWCC-Net） | ICCV 2023 | [arXiv:2306.01209](https://arxiv.org/abs/2306.01209) | [官方](https://github.com/awccnet/AWCC-Net) |
| Crowd Counting and Individual Localization Using Pseudo Square Label | IEEE Access 2024 | [DOI:10.1109/ACCESS.2024.3400310](https://doi.org/10.1109/ACCESS.2024.3400310) | - |
| CSCC: Cross-Scene Crowd Counting via Learning to Diversify for Domain Generalization | TMM 2025 | [DOI:10.1109/TMM.2025.3535302](https://doi.org/10.1109/TMM.2025.3535302) | - |
| D2PT: Density to Point Transformer with Knowledge Distillation for Crowd Counting and Localization | IEICE Trans. Inf. & Syst. 2025 | [DOI:10.1587/transinf.2024EDL8067](https://doi.org/10.1587/transinf.2024EDL8067) | - |
| Dataset-Level Directed Image Translation for Cross-Domain Crowd Counting | ICIP 2023 | [DOI:10.1109/ICIP49359.2023.10222458](https://doi.org/10.1109/ICIP49359.2023.10222458) | - |
| Free Lunch Enhancements for Multi-modal Crowd Counting | CVPR 2025 | [DOI:10.1109/CVPR52734.2025.01308](https://doi.org/10.1109/CVPR52734.2025.01308) | - |
| Learning Extremely High Density Crowds as Active Matters | arXiv 2025 | [arXiv:2503.12168](https://arxiv.org/abs/2503.12168) | - |
| Memory-efficient Cross-modal Attention for RGB-X Segmentation and Crowd Counting | Pattern Recognition 2025 | [DOI:10.1016/j.patcog.2025.111376](https://doi.org/10.1016/j.patcog.2025.111376) | - |
| MMCOUNT: Stationary Crowd Counting System Based on Commodity Millimeter-Wave Radar | ICASSP 2024 | [DOI:10.1109/ICASSP48485.2024.10447408](https://doi.org/10.1109/ICASSP48485.2024.10447408) | - |
| Perspective-assisted Prototype-based Learning for Semi-supervised Crowd Counting | Pattern Recognition 2025 | [DOI:10.1016/j.patcog.2024.111073](https://doi.org/10.1016/j.patcog.2024.111073) | - |
| Point-to-Region Loss for Semi-Supervised Point-Based Crowd Counting（P2RLoss） | CVPR 2025 | [DOI:10.1109/CVPR52734.2025.02734](https://doi.org/10.1109/CVPR52734.2025.02734) | [官方](https://github.com/Elin24/P2RLoss) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/170289436) |
| Progressive Self-supervised Learning: A Pre-training Method for Crowd Counting | Pattern Recognition Letters 2025 | [DOI:10.1016/j.patrec.2024.12.007](https://doi.org/10.1016/j.patrec.2024.12.007) | - |
| RestoCrowd: Image Restoration Coadjutant Learning for Hazy-weather Crowd Counting without Weather Labels | Pattern Recognition 2025 | [DOI:10.1016/j.patcog.2024.111291](https://doi.org/10.1016/j.patcog.2024.111291) | - |
| Single Domain Generalization for Few-Shot Counting via Universal Representation Matching | CVPR 2025 | [DOI:10.1109/CVPR52734.2025.00437](https://doi.org/10.1109/CVPR52734.2025.00437) | [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/156870771) / [视频](https://www.bilibili.com/video/BV16pDjBuE4r) |
| Taste More, Taste Better: Diverse Data and Strong Model Boost Semi-Supervised Crowd Counting（TMTB） | CVPR 2025 | [DOI:10.1109/CVPR52734.2025.02276](https://doi.org/10.1109/CVPR52734.2025.02276) / [arXiv:2503.17984](https://arxiv.org/abs/2503.17984) | [官方](https://github.com/syhien/taste_more_taste_better) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/148124251) |
| Weakly-Supervised Crowd Counting with Token Attention and Fusion: A Simple and Effective Baseline（WSCC_TAF） | ICASSP 2024 | [DOI:10.1109/ICASSP48485.2024.10446636](https://doi.org/10.1109/ICASSP48485.2024.10446636) | [官方](https://github.com/WangyiNTU/WSCC_TAF) |
| ZIP: Scalable Crowd Counting via Zero-Inflated Poisson Modeling | 期刊待定 | [Scholar](https://scholar.google.com/scholar?q=%22ZIP%3A+Scalable+Crowd+Counting+via+Zero-Inflated+Poisson+Modeling%22) | - |
| RP-Net: A Robust Polar Transformation Network for Rotation-invariant Face Detection（人脸检测） | Pattern Recognition 2025 | [DOI:10.1016/j.patcog.2024.111044](https://doi.org/10.1016/j.patcog.2024.111044) | - |

### 2026

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| CrowdCL: Unsupervised Crowd Counting Network via Contrastive Learning | IEEE IoT Journal 2025 | [DOI:10.1109/JIOT.2025.3547898](https://doi.org/10.1109/JIOT.2025.3547898) | - |
| Single Domain Generalization Crowd Counting via Hybrid Space Fusion and Contrastive Disentanglement Learning | Applied Soft Computing 2026 | [DOI:10.1016/j.asoc.2026.114862](https://doi.org/10.1016/j.asoc.2026.114862) | - |

---

## 三、其他经典论文

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| An Aggregated Multicolumn Dilated Convolution Network for Perspective-Free Counting（AMDCN） | CVPRW 2018 | [CVF](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w6/Deb_An_Aggregated_Multicolumn_CVPR_2018_paper.pdf) | [官方](https://github.com/diptodip/counting) |
| Attention Scaling for Crowd Counting（ASNet） | CVPR 2020 | [CVF](http://openaccess.thecvf.com/content_CVPR_2020/papers/Jiang_Attention_Scaling_for_Crowd_Counting_CVPR_2020_paper.pdf) | [官方](https://github.com/laridzhang/ASNet) |
| Adversarial Learning for Multiscale Crowd Counting Under Complex Scenes（MS-GAN） | IEEE TCYB 2021 | [IEEE](https://ieeexplore.ieee.org/document/8949751) | - |
| Attend to Count: Crowd Counting with Adaptive Capacity Multi-scale CNNs（ACM-CNN） | Neurocomputing 2019 | [DOI:10.1016/j.neucom.2019.08.009](https://doi.org/10.1016/j.neucom.2019.08.009) | - |
| Bi-level Alignment for Cross-Domain Crowd Counting（BLA） | CVPR 2022 | [arXiv:2205.05844](https://arxiv.org/abs/2205.05844) | [官方](https://github.com/Yankeegsj/BLA) |
| Counting with Focus for Free（CFF） | ICCV 2019 | [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Shi_Counting_With_Focus_for_Free_ICCV_2019_paper.pdf) | [官方](https://github.com/shizenglin/Counting-with-Focus-for-Free) |
| Focus for Free in Density-Based Counting（CFF 期刊扩展版） | IJCV 2024 | [arXiv:2306.05129](https://arxiv.org/abs/2306.05129) | [官方](https://github.com/shizenglin/Counting-with-Focus-for-Free) |
| Crowd Counting in the Frequency Domain（ChfL） | CVPR 2022 | [CVF](https://openaccess.thecvf.com/content/CVPR2022/papers/Shu_Crowd_Counting_in_the_Frequency_Domain_CVPR_2022_paper.pdf) | [官方](https://github.com/wbshu/Crowd_Counting_in_the_Frequency_Domain) |
| Cross-Level Parallel Network for Crowd Counting（CLPNet） | TII 2020 | [DOI:10.1109/TII.2019.2935244](https://doi.org/10.1109/TII.2019.2935244) | - |
| DADNet: Dilated-Attention-Deformable ConvNet for Crowd Counting | ACM MM 2019 | [DOI:10.1145/3343031.3350881](https://doi.org/10.1145/3343031.3350881) | - |
| DENet: A Universal Network for Counting Crowd with Varying Densities and Scales | TMM 2021 | [arXiv:1904.08056](https://arxiv.org/abs/1904.08056) | [官方](https://github.com/liuleiBUAA/DENet) |
| Domain Generalization via Gradient Surgery（DGvGS） | ICCV 2021 | [arXiv:2108.01621](https://arxiv.org/abs/2108.01621) | [官方](https://github.com/lucasmansilla/DGvGS) |
| Focal Inverse Distance Transform Maps for Crowd Localization（FIDTM） | TMM 2022 | [DOI:10.1109/TMM.2022.3203870](https://doi.org/10.1109/TMM.2022.3203870) | [官方](https://github.com/dk-liang/FIDTM) |
| Rethinking Spatial Invariance of Convolutional Networks for Object Counting（GauNet） | CVPR 2022 | [arXiv:2206.05253](https://arxiv.org/abs/2206.05253) | [官方](https://github.com/zhiqic/Rethinking-Counting) |
| Harnessing Perceptual Adversarial Patches for Crowd Counting（PAP） | ACM CCS 2022 | [DOI:10.1145/3548606.3560566](https://doi.org/10.1145/3548606.3560566) / [arXiv:2109.07986](https://arxiv.org/abs/2109.07986) | [官方](https://github.com/shunchang-liu/PAP-Pytorch) |
| Improving the Learning of Multi-column Convolutional Neural Network for Crowd Counting（McML） | ACM MM 2019 | [DOI:10.1145/3343031.3350898](https://doi.org/10.1145/3343031.3350898) | - |
| Learning to Count with CNN Boosting | ECCV 2016 | [DOI:10.1007/978-3-319-46475-6_41](https://doi.org/10.1007/978-3-319-46475-6_41) | - |
| Learning To Count Everything（FamNet） | ECCV 2018 | [arXiv:2104.08391](https://arxiv.org/abs/2104.08391) | [官方](https://github.com/cvlab-stonybrook/LearningToCountEverything) |
| Boosting Crowd Counting via Multifaceted Attention（MAN） | CVPR 2022 | [DOI:10.1109/CVPR52688.2022.01901](https://doi.org/10.1109/CVPR52688.2022.01901) / [arXiv:2203.02636](https://arxiv.org/abs/2203.02636) | [官方](https://github.com/LoraLinH/Boosting-Crowd-Counting-via-Multifaceted-Attention) |
| Neuron Linear Transformation: Modeling the Domain Shift for Crowd Counting（NLT） | TNNLS 2021 | [arXiv:2004.02133](https://arxiv.org/abs/2004.02133) | [官方](https://github.com/taohan10200/NLT) |
| Nonlinear Regression via Deep Negative Correlation Learning（DNCL） | TPAMI 2019 | [IEEE](https://ieeexplore.ieee.org/document/8850209) / [项目主页](https://mmcheng.net/dncl/) | - |
| RobustNet: Improving Domain Generalization in Urban-Scene Segmentation via Instance Selective Whitening | CVPR 2021 | [DOI:10.1109/CVPR46437.2021.01141](https://doi.org/10.1109/CVPR46437.2021.01141) / [arXiv:2103.00262](https://arxiv.org/abs/2103.00262) | [官方](https://github.com/shachoi/RobustNet) |
| SCAR: Spatial-/Channel-wise Attention Regression Networks for Crowd Counting | Neurocomputing 2019 | [arXiv:1908.03716](https://arxiv.org/abs/1908.03716) | [官方](https://github.com/gjy3035/SCAR) |
| Switchable Whitening for Deep Representation Learning（SW） | ICCV 2019 | [DOI:10.1109/ICCV.2019.00195](https://doi.org/10.1109/ICCV.2019.00195) / [arXiv:1904.09739](https://arxiv.org/abs/1904.09739) | [官方](https://github.com/XingangPan/Switchable-Whitening) |
| Composition Loss for Counting, Density Map Estimation and Localization in Dense Crowds（UCF-QNRF 数据集论文） | ECCV 2018 | [DOI:10.1007/978-3-030-01216-8_33](https://doi.org/10.1007/978-3-030-01216-8_33) | - |
| Privacy Preserving Crowd Monitoring: Counting People without People Models or Tracking（UCSD 数据集论文） | CVPR 2008 | [DOI:10.1109/CVPR.2008.4587569](https://doi.org/10.1109/CVPR.2008.4587569) | - |

---

## 四、专题方向论文

### 4.1 跨域与域适应（Cross-Domain / Domain Adaptation）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Cross-Domain Adaptive Clustering for Semi-Supervised Domain Adaptation（CDAC） | CVPR 2021 | [DOI:10.1109/CVPR46437.2021.00253](https://doi.org/10.1109/CVPR46437.2021.00253) | [官方](https://github.com/jichangli/Cross-Domain-Adaptive-Clustering) |
| Leveraging Self-Supervision for Cross-Domain Crowd Counting（CDCC / SFCN） | CVPR 2022 (Oral) | [DOI:10.1109/CVPR52688.2022.00527](https://doi.org/10.1109/CVPR52688.2022.00527) / [arXiv:2103.16291](https://arxiv.org/abs/2103.16291) | [官方](https://github.com/weizheliu/Cross-Domain-Crowd-Counting) |

### 4.2 其他新论文

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Consistent-Point: Consistent Pseudo-Points for Semi-Supervised Crowd Counting and Localization | arXiv 2025 | [arXiv:2503.12441](https://arxiv.org/abs/2503.12441) | [复现](https://github.com/KeepTryingTo/Consistent-Point) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/169744882) / [视频](https://www.bilibili.com/video/BV1Lfxi6fEFU) |
| L2HCount: Generalizing Crowd Counting from Low to High Crowd Density via Density Simulation | arXiv 2025 | [arXiv:2503.12935](https://arxiv.org/abs/2503.12935) | - |
| RCCFormer: A Robust Crowd Counting Network Based on Transformer | Measurement 2025 | [DOI:10.2139/ssrn.5295630](https://doi.org/10.2139/ssrn.5295630) / [Scholar](https://scholar.google.com/scholar?q=RCCFormer+Robust+Crowd+Counting+Transformer) | - |
| Transformer-Based Dual-Optical Attention Fusion Crowd Head Point Counting and Localization Network | 期刊待定 | [Scholar](https://scholar.google.com/scholar?q=%22Transformer-Based+Dual-Optical+Attention+Fusion+Crowd+Head+Point%22) | - |

### 4.3 点回归框架（Point-based Framework）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| An End-to-End Transformer Model for Crowd Localization（CLTR） | ECCV 2022 | [arXiv:2202.13065](https://arxiv.org/abs/2202.13065) | [官方](https://github.com/dk-liang/CLTR) |
| Point-Query Quadtree for Crowd Counting, Localization, and More（PET） | ICCV 2023 | [DOI:10.1109/ICCV51070.2023.00161](https://doi.org/10.1109/ICCV51070.2023.00161) / [arXiv:2308.13814](https://arxiv.org/abs/2308.13814) | [官方](https://github.com/cxliu0/PET) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/170289534) |
| Decoupled Two-Stage Crowd Counting and Beyond（D2CNet） | TIP 2021 | [DOI:10.1109/TIP.2021.3055631](https://doi.org/10.1109/TIP.2021.3055631) | [官方](https://github.com/hustaia/Decoupled_Two-Stage_Counting) |

### 4.4 半监督人群计数（Semi-supervised）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| A Benchmark for Semi-supervised Multi-modal Crowd Counting | arXiv 2026 | [arXiv:2606.03646](https://arxiv.org/abs/2606.03646) | - |
| ACENet: Contextual Graph Reasoning for Semi-supervised Crowd Counting | Expert Systems with Applications 2026 | [DOI:10.1016/j.eswa.2026.132685](https://doi.org/10.1016/j.eswa.2026.132685) | - |
| Boosting Semi-supervised Crowd Counting with Scale-based Active Learning（SAL） | ACM MM 2024 | [DOI:10.1145/3664647.3680976](https://doi.org/10.1145/3664647.3680976) / [OpenReview](https://openreview.net/pdf?id=AXvAc3HQFl) | [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/170289502) / [视频](https://www.bilibili.com/video/BV1hFJt61Ehg) |
| Calibrating Uncertainty for Semi-Supervised Crowd Counting | ICCV 2023 | [DOI:10.1109/ICCV51070.2023.01534](https://doi.org/10.1109/ICCV51070.2023.01534) / [arXiv:2308.09887](https://arxiv.org/abs/2308.09887) | [官方](https://github.com/superlc1995/Calibrating_count) / [复现](https://github.com/KeepTryingTo/Uncertainty-Semi-Supervised-Crowd-Counting) / [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/169653058) |
| Exclusivity-Guided Mask Learning for Semi-Supervised Crowd Instance Segmentation and Counting | ECCVW / LNCS 2026 | [DOI:10.1007/978-3-032-37225-3_37](https://doi.org/10.1007/978-3-032-37225-3_37) | [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/167130146) |
| Exploiting Highly Inconsistent Image Regions for Active Semi-Supervised Crowd Counting | IEEE SPL 2026 | [DOI:10.1109/LSP.2026.3676320](https://doi.org/10.1109/LSP.2026.3676320) | - |
| Semi-Supervised Crowd Counting with Contextual Modeling: Facilitating Holistic Understanding of Crowd Scenes（MRC-Crowd） | TCSVT 2024 | [DOI:10.1109/TCSVT.2024.3392500](https://doi.org/10.1109/TCSVT.2024.3392500) / [arXiv:2310.10352](https://arxiv.org/abs/2310.10352) | [官方](https://github.com/cha15yq/MRC-Crowd) |
| Multi-Task Credible Pseudo-Label Learning for Semi-supervised Crowd Counting（MTCP） | TNNLS 2024 | [DOI:10.1109/TNNLS.2023.3241211](https://doi.org/10.1109/TNNLS.2023.3241211) | [官方](https://github.com/ljq2000/MTCP) |
| Optimal Transport Minimization: Crowd Localization on Density Maps for Semi-Supervised Counting（OT-M） | CVPR 2023 | [DOI:10.1109/CVPR52729.2023.02075](https://doi.org/10.1109/CVPR52729.2023.02075) / [CVF](https://openaccess.thecvf.com/content/CVPR2023/papers/Lin_Optimal_Transport_Minimization_Crowd_Localization_on_Density_Maps_for_Semi-Supervised_CVPR_2023_paper.pdf) | [官方](https://github.com/Elin24/OT-M) |
| Semi-Supervised Crowd Counting from Unlabeled Data | Pattern Recognition 2026 | [DOI:10.1016/j.patcog.2025.112787](https://doi.org/10.1016/j.patcog.2025.112787) | - |
| Semi-Supervised Crowd Counting Method Based on Masked Image Modeling | ICACTE 2025 | [DOI:10.1109/ICACTE66284.2025.11412176](https://doi.org/10.1109/ICACTE66284.2025.11412176) | - |
| Semi-Supervised Crowd Counting via Self-Training on Surrogate Tasks（IRAST） | ECCV 2020 | [arXiv:2007.03207](https://arxiv.org/abs/2007.03207) | - |
| Semi-Supervised Crowd Counting via Swin Transformer with Adaptive Soft Threshold and Contrastive Learning | ACM TIST 2026 | [DOI:10.1145/3744747](https://doi.org/10.1145/3744747) | - |
| Semi-Supervised Multi-View Crowd Counting by Ranking Multi-View Fusion Models | 期刊待定 | [Scholar](https://scholar.google.com/scholar?q=%22Semi-Supervised+Multi-View+Crowd+Counting+by+Ranking%22) | - |
| Spatial Uncertainty-Aware Semi-Supervised Crowd Counting（SUA） | ICCV 2021 | [DOI:10.1109/ICCV48922.2021.01526](https://doi.org/10.1109/ICCV48922.2021.01526) / [arXiv:2107.13271](https://arxiv.org/abs/2107.13271) | [官方](https://github.com/smallmax00/SUA_crowd_counting) |
| SLIC Superpixels Compared to State-of-the-art Superpixel Methods | TPAMI 2012 | [DOI:10.1109/TPAMI.2012.120](https://doi.org/10.1109/TPAMI.2012.120) | - |

### 4.5 RGB-T 多模态人群计数（Multi-modal）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| CSAFNet: Cross-modal Spatial Alignment and Fusion Network for RGB-T Crowd Counting | Pattern Recognition 2026 | [DOI:10.1016/j.patcog.2026.113250](https://doi.org/10.1016/j.patcog.2026.113250) | - |
| A Mutual Head Knowledge Distillation Framework for Lightweight RGB-T Crowd Counting | TCSVT 2025 | [DOI:10.1109/TCSVT.2025.3588815](https://doi.org/10.1109/TCSVT.2025.3588815) | - |
| MAFNet: A Multi-Attention Fusion Network for RGB-T Crowd Counting | arXiv 2022 | [arXiv:2208.06761](https://arxiv.org/abs/2208.06761) | - |
| MISF-Net: Modality-Invariant and -Specific Fusion Network for RGB-T Crowd Counting | TMM 2025 | [DOI:10.1109/TMM.2025.3535330](https://doi.org/10.1109/TMM.2025.3535330) | - |
| Multimodal Crowd Counting with Mutual Attention Transformers（MMAF） | ICME 2022 | [DOI:10.1109/ICME52920.2022.9859777](https://doi.org/10.1109/ICME52920.2022.9859777) | - |
| RGB-T Crowd Counting from Drone: A Benchmark and MMCCN Network（DroneRGBT 数据集） | 期刊待定 | [Scholar](https://scholar.google.com/scholar?q=%22RGB-T+Crowd+Counting+from+Drone%22)（改进版 I-MMCCN: [DOI:10.1109/IC-NIDC54101.2021.9660586](https://doi.org/10.1109/IC-NIDC54101.2021.9660586)） | - |
| RGBT-Booster: Detail-Boosted Fusion Network for RGB-Thermal Crowd Counting with Local Contrastive Learning | IEEE IoT Journal 2025 | [DOI:10.1109/JIOT.2025.3540867](https://doi.org/10.1109/JIOT.2025.3540867) | - |
| RGB-T Multi-Modal Crowd Counting Based on Transformer（MSDTrans） | BMVC 2022 | [arXiv:2301.03033](https://arxiv.org/abs/2301.03033) | [官方（RGBTCC）](https://github.com/liuzywen/RGBTCC) |

### 4.6 视频人群计数（Video Crowd Counting）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Triple Attention for Robust Video Crowd Counting | ICIP 2020 | [DOI:10.1109/ICIP40778.2020.9190701](https://doi.org/10.1109/ICIP40778.2020.9190701) | - |
| ICIAP 2022 会议论文集（LNCS 13233） | Springer 2022 | [DOI:10.1007/978-3-031-06433-3](https://doi.org/10.1007/978-3-031-06433-3) | - |
| A Novel Cascaded Deep Architecture with Weak-supervision for Video Crowd Counting and Density Estimation | Soft Computing 2024 | [DOI:10.1007/s00500-024-09681-4](https://doi.org/10.1007/s00500-024-09681-4) | - |
| A Novel Framework for Crowd Counting Using Video and Audio | Computers and Electrical Engineering 2023 | [DOI:10.1016/j.compeleceng.2023.108754](https://doi.org/10.1016/j.compeleceng.2023.108754) | - |
| CLRNet: A Cross Locality Relation Network for Crowd Counting in Videos | TNNLS 2024 | [IEEE](https://ieeexplore.ieee.org/document/9913683) | - |
| Crowded Video Individual Counting Informed by Social Grouping and Spatial-Temporal Displacement Priors（SGNet） | TIP 2026 | [DOI:10.1109/TIP.2026.3737046](https://doi.org/10.1109/TIP.2026.3737046) | - |
| DR.VIC: Decomposition and Reasoning for Video Individual Counting | CVPR 2022 | [PDF](https://crabwq.github.io/pdf/2022%20DR.VIC.pdf) | [官方（DRNet）](https://github.com/taohan10200/DRNet) |
| Dual-branch Adjacent Connection and Channel Mixing Network for Video Crowd Counting | Pattern Recognition 2025 | [DOI:10.1016/j.patcog.2025.111709](https://doi.org/10.1016/j.patcog.2025.111709) | - |
| Fast Video Crowd Counting with a Temporal Aware Network（TAN） | Neurocomputing 2020 | [arXiv:1907.02198](https://arxiv.org/abs/1907.02198) | - |
| Frame-Recurrent Video Crowd Counting（FRVCC） | TCSVT 2023 | [IEEE](https://ieeexplore.ieee.org/document/10057072) | - |
| GFAF-Net: Global–Local Feature Extraction and Adaptive Fusion Network for RGB-T Crowd Counting in Video Surveillance Systems | TASE 2026 | [DOI:10.1109/TASE.2026.3681332](https://doi.org/10.1109/TASE.2026.3681332) | - |
| Global Representation Guided Adaptive Fusion Network for Stable Video Crowd Counting | TMM 2023 | [DOI:10.1109/TMM.2022.3189246](https://doi.org/10.1109/TMM.2022.3189246) | - |
| Heterogeneous Dual-Attentional Network for WiFi and Video-Fused Multi-Modal Crowd Counting | TMC 2024 | [DOI:10.1109/TMC.2024.3444469](https://doi.org/10.1109/TMC.2024.3444469) | - |
| Locality-Constrained Spatial Transformer Network for Video Crowd Counting（LSTN） | ICME 2019 (Oral) | [arXiv:1907.07911](https://arxiv.org/abs/1907.07911) | - |
| Motion-guided Non-local Spatial-Temporal Network for Video Crowd Counting | arXiv 2021 | [arXiv:2104.13946](https://arxiv.org/abs/2104.13946) | - |
| Motional Foreground Attention-based Video Crowd Counting | Pattern Recognition 2023 | [DOI:10.1016/j.patcog.2023.109891](https://doi.org/10.1016/j.patcog.2023.109891) | - |
| PointerNet: Spatiotemporal Modeling for Crowd Counting in Videos | ICAET 2021 | [DOI:10.1145/3480001.3480018](https://doi.org/10.1145/3480001.3480018) | - |
| AMS-CNN: Attentive Multi-stream CNN for Video-based Crowd Counting | IJMIR 2021 | [DOI:10.1007/s13735-021-00220-7](https://doi.org/10.1007/s13735-021-00220-7) | - |
| Scene-Adaptive Unsupervised Crowd Counting for Video Surveillance | TCSVT 2025 | [DOI:10.1109/TCSVT.2025.3540850](https://doi.org/10.1109/TCSVT.2025.3540850) | - |
| Spatiotemporal Modeling for Crowd Counting in Videos（ConvLSTM） | ICCV 2017 | [CVF](http://openaccess.thecvf.com/content_ICCV_2017/papers/Xiong_Spatiotemporal_Modeling_for_ICCV_2017_paper.pdf) | - |
| Statistical Video Analysis for Crowds Counting（Albiol） | ICIP 2009 | [DOI:10.1109/ICIP.2009.5414002](https://doi.org/10.1109/ICIP.2009.5414002) | - |
| Video Crowd Counting via Dynamic Temporal Modeling | 期刊待定 | [Scholar](https://scholar.google.com/scholar?q=%22Video+Crowd+Counting+via+Dynamic+Temporal+Modeling%22) | - |

### 4.7 密度图生成与标注质量（Density Map Generation & Annotation）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| A Generalized Loss Function for Crowd Counting and Localization（GLoss） | CVPR 2021 | [DOI:10.1109/CVPR46437.2021.00201](https://doi.org/10.1109/CVPR46437.2021.00201) / [CVF](https://openaccess.thecvf.com/content/CVPR2021/papers/Wan_A_Generalized_Loss_Function_for_Crowd_Counting_and_Localization_CVPR_2021_paper.pdf) | - |
| Fine-Grained Crowd Counting（FGCC） | TIP 2020 | [DOI:10.1109/TIP.2021.3049938](https://doi.org/10.1109/TIP.2021.3049938) / [arXiv:2007.06146](https://arxiv.org/abs/2007.06146) | - |
| Kernel-based Density Map Generation for Dense Object Counting（KDMG） | TPAMI 2021 | [DOI:10.1109/TPAMI.2020.3022878](https://doi.org/10.1109/TPAMI.2020.3022878) | [官方](https://github.com/jia-wan/KDMG_Counting) |
| Modeling Noisy Annotations for Crowd Counting（MNA） | NeurIPS 2020 | [PDF](http://visal.cs.cityu.edu.hk/static/pubs/conf/nips2020-noisycc-web.pdf) | - |
| Adaptive Density Map Generation for Crowd Counting（ADMG） | ICCV 2019 | [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wan_Adaptive_Density_Map_Generation_for_Crowd_Counting_ICCV_2019_paper.pdf) | - |

### 4.8 白化与风格迁移基础论文（Whitening & Style Transfer）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Image-to-Image Translation via Group-wise Deep Whitening-and-Coloring Transformation（GDWCT） | CVPR 2019 | [arXiv:1812.09912](https://arxiv.org/abs/1812.09912) | - |
| Image Style Transfer Using Convolutional Neural Networks（Gatys） | CVPR 2016 | [arXiv:1508.06576](https://arxiv.org/abs/1508.06576) | - |
| Texture Synthesis Using Convolutional Neural Networks | arXiv 2015 | [arXiv:1505.07376](https://arxiv.org/abs/1505.07376) | - |
| Universal Style Transfer via Feature Transforms（WCT） | ECCV 2017 | [arXiv:1705.08086](https://arxiv.org/abs/1705.08086) | - |

### 4.9 相关基础论文（损失函数 / 课程学习 / 深度估计 / 分割）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| Learning Crowd Scale and Distribution for Weakly Supervised Crowd Counting and Localization | TCSVT 2025 | [DOI:10.1109/TCSVT.2024.3460482](https://doi.org/10.1109/TCSVT.2024.3460482) | - |
| Crowd Counting with Partial Annotations in an Image（URC） | ICCV 2021 | [CVF](https://openaccess.thecvf.com/content/ICCV2021/papers/Xu_Crowd_Counting_With_Partial_Annotations_in_an_Image_ICCV_2021_paper.pdf) | - |
| From Semi-Supervised to Transfer Counting of Crowds（SSR） | ICCV 2013 | [CVF](https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Loy_From_Semi-supervised_to_2013_ICCV_paper.pdf) | - |
| Class-Balanced Loss Based on Effective Number of Samples | CVPR 2019 | [arXiv:1901.05555](https://arxiv.org/abs/1901.05555) | - |
| Focal Loss for Dense Object Detection | ICCV 2017 | [arXiv:1708.02002](https://arxiv.org/abs/1708.02002) | - |
| A Survey on Curriculum Learning | TPAMI 2021 | [arXiv:2012.09124](https://arxiv.org/abs/2012.09124) | - |
| Self-Paced Curriculum Learning | ICML 2015 | [arXiv:1504.05188](https://arxiv.org/abs/1504.05188) | - |
| Self-Paced Learning for Latent Variable Models | NeurIPS 2010 | [NeurIPS](https://papers.nips.cc/paper/3923-self-paced-learning-for-latent-variable-models) | - |
| Global-Local Path Networks for Monocular Depth Estimation with Vertical CutDepth（GLPNet） | ICCV 2021 | [arXiv:2201.07436](https://arxiv.org/abs/2201.07436) | [官方](https://github.com/vinvino02/PGLDepthEstimation) |
| SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers | NeurIPS 2021 | [arXiv:2105.15203](https://arxiv.org/abs/2105.15203) | [官方](https://github.com/NVlabs/SegFormer) |

### 4.10 轻量化模型与知识蒸馏（Light-weight & Knowledge Distillation）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| A Real-Time Deep Network for Crowd Counting（C-CNN） | ICASSP 2020 | [arXiv:2002.06515](https://arxiv.org/abs/2002.06515) | - |
| Beyond ImageNet: Understanding Cross-Dataset Robustness of Lightweight Vision Models | Algorithms 2025 | [DOI:10.3390/a19010014](https://doi.org/10.3390/a19010014) / [arXiv:2511.00335](https://arxiv.org/abs/2511.00335) | - |
| Context-Aware Crowd Counting（CAN） | CVPR 2019 | [arXiv:1811.10452](https://arxiv.org/abs/1811.10452) | [官方](https://github.com/weizheliu/Context-Aware-Crowd-Counting) |
| DistillFSS: Synthesizing Few-Shot Knowledge into a Lightweight Segmentation Model | 期刊待定 | [Scholar](https://scholar.google.com/scholar?q=%22DistillFSS%3A+Synthesizing+Few-Shot+Knowledge%22) | - |
| Efficient Crowd Counting via Structured Knowledge Transfer（SKT） | ACM MM 2020 (Oral) | [DOI:10.1145/3394171.3413938](https://doi.org/10.1145/3394171.3413938) / [arXiv:2003.10120](https://arxiv.org/abs/2003.10120) | [官方](https://github.com/HCPLab-SYSU/SKT) |
| Fuss-Free Network: A Simplified and Efficient Neural Network for Crowd Counting（FFNet） | arXiv 2024 | [arXiv:2404.07847](https://arxiv.org/abs/2404.07847) | [博客](https://blog.csdn.net/Keep_Trying_Go/article/details/141355068) |
| FusionCount: Efficient Crowd Counting via Multiscale Feature Fusion | ICIP 2022 | [DOI:10.1109/ICIP46576.2022.9897322](https://doi.org/10.1109/ICIP46576.2022.9897322) / [arXiv:2202.13660](https://arxiv.org/abs/2202.13660) | [官方](https://github.com/YimingMa/FusionCount) |
| Improved Knowledge Distillation for Crowd Counting on IoT Devices | IEEE EDGE 2023 | [DOI:10.1109/EDGE60047.2023.00041](https://doi.org/10.1109/EDGE60047.2023.00041) | - |
| Lightweight Multi-scale Network with Attention for Accurate and Efficient Crowd Counting | The Visual Computer 2024 | [DOI:10.1007/s00371-023-03099-z](https://doi.org/10.1007/s00371-023-03099-z) | - |
| LWGANet: Addressing Spatial and Channel Redundancy in Remote Sensing Visual Tasks with Light-Weight Grouped Attention | AAAI 2026 | [DOI:10.1609/aaai.v40i9.37698](https://doi.org/10.1609/aaai.v40i9.37698) / [arXiv:2501.10040](https://arxiv.org/abs/2501.10040) | - |
| MobileCount: An Efficient Encoder-Decoder Framework for Real-Time Crowd Counting | Neurocomputing 2020 | [DOI:10.1016/j.neucom.2020.05.056](https://doi.org/10.1016/j.neucom.2020.05.056) | [非官方](https://github.com/SelinaFelton/MobileCount) |
| PDDNet: Lightweight Congested Crowd Counting via Pyramid Depth-wise Dilated Convolution | Applied Intelligence 2023 | [DOI:10.1007/s10489-022-03967-6](https://doi.org/10.1007/s10489-022-03967-6) | - |
| Real-time Crowd Counting via Lightweight Scale-aware Network（LSANet） | Neurocomputing 2022 | [DOI:10.1016/j.neucom.2021.11.099](https://doi.org/10.1016/j.neucom.2021.11.099) | - |
| Reducing Capacity Gap in Knowledge Distillation with Review Mechanism for Crowd Counting | arXiv 2022 | [arXiv:2206.05475](https://arxiv.org/abs/2206.05475) | - |
| Boundary Loss for Highly Unbalanced Segmentation | Medical Image Analysis 2019 | [DOI:10.1016/j.media.2020.101851](https://doi.org/10.1016/j.media.2020.101851) / [arXiv:1812.07003](https://arxiv.org/abs/1812.07003) | - |
| A Computational Approach to Edge Detection（Canny） | TPAMI 1986 | [DOI:10.1109/TPAMI.1986.4767851](https://doi.org/10.1109/TPAMI.1986.4767851) | - |

### 4.11 目标检测相关（YOLOv13）

| 论文标题 | 发表 | 论文链接 | 代码 |
|---|---|---|---|
| YOLOv13: Real-Time Object Detection with Hypergraph-Enhanced Adaptive Visual Perception | arXiv 2025 | [arXiv:2506.17733](https://arxiv.org/abs/2506.17733) | [官方](https://github.com/iMoonLab/yolov13) |

---

## 五、代码仓库汇总

### 5.1 论文对应代码仓库

| 项目 | 对应论文 / 说明 | 论文链接 | 代码链接 |
|---|---|---|---|
| C^3 Framework | C^3 Framework（人群计数开源训练框架） | [arXiv:1907.02724](https://arxiv.org/abs/1907.02724) | [gjy3035/C-3-Framework](https://github.com/gjy3035/C-3-Framework) |
| Bayesian Loss | Bayesian Loss（ICCV 2019） | [CVF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Ma_Bayesian_Loss_for_Crowd_Count_Estimation_With_Point_Supervision_ICCV_2019_paper.pdf) | [ZhihengCV/Bayesian-Crowd-Counting](https://github.com/ZhihengCV/Bayesian-Crowd-Counting) |
| BLA | Bi-level Alignment for Cross-Domain Crowd Counting（CVPR 2022） | [arXiv:2205.05844](https://arxiv.org/abs/2205.05844) | [Yankeegsj/BLA](https://github.com/Yankeegsj/BLA) |
| P2PNet | Rethinking Counting and Localization in Crowds（ICCV 2021 Oral） | [arXiv:2107.12746](https://arxiv.org/abs/2107.12746) | [TencentYoutuResearch/CrowdCounting-P2PNet](https://github.com/TencentYoutuResearch/CrowdCounting-P2PNet) |
| CSS-CCNN | Completely Self-Supervised Crowd Counting via Distribution Matching | [arXiv:2009.06420](https://arxiv.org/abs/2009.06420) | [val-iisc/css-ccnn](https://github.com/val-iisc/css-ccnn) |
| DeepCount | Deep Density-aware Count Regressor（ECAI 2020） | [arXiv:1908.03314](https://arxiv.org/abs/1908.03314) | [GeorgeChenZJ/deepcount](https://github.com/GeorgeChenZJ/deepcount) |
| CLTR | An End-to-End Transformer Model for Crowd Localization（ECCV 2022） | [arXiv:2202.13065](https://arxiv.org/abs/2202.13065) | [dk-liang/CLTR](https://github.com/dk-liang/CLTR) |
| TransCrowd | TransCrowd: Weakly-Supervised Crowd Counting with Transformer | [arXiv:2104.09116](https://arxiv.org/abs/2104.09116) | [dk-liang/TransCrowd](https://github.com/dk-liang/TransCrowd) |
| CrowdCLIP | CrowdCLIP: Unsupervised Crowd Counting via Vision-Language Model（CVPR 2023） | [arXiv:2304.04231](https://arxiv.org/abs/2304.04231) | [dk-liang/CrowdCLIP](https://github.com/dk-liang/CrowdCLIP) |
| PET | Point-Query Quadtree for Crowd Counting, Localization, and More（ICCV 2023） | [arXiv:2308.13814](https://arxiv.org/abs/2308.13814) | [cxliu0/PET](https://github.com/cxliu0/PET) |
| OT-M | Optimal Transport Minimization（CVPR 2023） | [CVF](https://openaccess.thecvf.com/content/CVPR2023/papers/Lin_Optimal_Transport_Minimization_Crowd_Localization_on_Density_Maps_for_Semi-Supervised_CVPR_2023_paper.pdf) | [Elin24/OT-M](https://github.com/Elin24/OT-M) |
| P2RLoss | Point-to-Region Loss for Semi-Supervised Point-Based Crowd Counting（CVPR 2025） | [DOI:10.1109/CVPR52734.2025.02734](https://doi.org/10.1109/CVPR52734.2025.02734) | [Elin24/P2RLoss](https://github.com/Elin24/P2RLoss) |
| D2CNet | Decoupled Two-Stage Crowd Counting and Beyond（TIP 2021） | [IEEE](https://ieeexplore.ieee.org/document/9347700) | [hustaia/Decoupled_Two-Stage_Counting](https://github.com/hustaia/Decoupled_Two-Stage_Counting) |
| DACount | Semi-supervised Crowd Counting via Density Agency（ACM MM 2022） | [arXiv:2209.02955](https://arxiv.org/abs/2209.02955) | [LoraLinH/Semi-supervised-Crowd-Counting-via-Density-Agency](https://github.com/LoraLinH/Semi-supervised-Crowd-Counting-via-Density-Agency) |
| Calibrating Uncertainty（复现） | Calibrating Uncertainty for Semi-Supervised Crowd Counting（ICCV 2023） | [DOI:10.1109/ICCV51070.2023.01534](https://doi.org/10.1109/ICCV51070.2023.01534) / [arXiv:2308.09887](https://arxiv.org/abs/2308.09887) | [KeepTryingTo/Uncertainty-Semi-Supervised-Crowd-Counting](https://github.com/KeepTryingTo/Uncertainty-Semi-Supervised-Crowd-Counting)（官方：[superlc1995/Calibrating_count](https://github.com/superlc1995/Calibrating_count)） |
| Consistent-Point（复现） | Consistent-Point: Consistent Pseudo-Points for Semi-Supervised Crowd Counting and Localization（arXiv 2025） | [arXiv:2503.12441](https://arxiv.org/abs/2503.12441) | [KeepTryingTo/Consistent-Point](https://github.com/KeepTryingTo/Consistent-Point) |
| TMTB | Taste More, Taste Better（CVPR 2025） | [arXiv:2503.17984](https://arxiv.org/abs/2503.17984) | [syhien/taste_more_taste_better](https://github.com/syhien/taste_more_taste_better) |
| MPCount | Single Domain Generalization for Crowd Counting（CVPR 2024） | [arXiv:2403.09124](https://arxiv.org/abs/2403.09124) | [Shimmer93/MPCount](https://github.com/Shimmer93/MPCount) |
| Broker Modality | Multi-modal Crowd Counting via a Broker Modality（ECCV 2024） | [arXiv:2407.07518](https://arxiv.org/abs/2407.07518) | [HenryCilence/Broker-Modality-Crowd-Counting](https://github.com/HenryCilence/Broker-Modality-Crowd-Counting) |
| CLIP-EBC | CLIP-EBC（arXiv 2024 / ICME 2025） | [arXiv:2403.09281](https://arxiv.org/abs/2403.09281) | [Yiming-M/CLIP-EBC](https://github.com/Yiming-M/CLIP-EBC) |
| Crowd-Hat | Boosting Detection in Crowd Analysis via Underutilized Output Features（CVPR 2023） | [CVF](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_Boosting_Detection_in_Crowd_Analysis_via_Underutilized_Output_Features_CVPR_2023_paper.pdf) | [wskingdom/Crowd-Hat](https://github.com/wskingdom/Crowd-Hat) |
| CrowdDiff | CrowdDiff（CVPR 2024） | [CVF](https://openaccess.thecvf.com/content/CVPR2024/papers/Ranasinghe_CrowdDiff_Multi-hypothesis_Crowd_Density_Estimation_using_Diffusion_Models_CVPR_2024_paper.pdf) | [dylran/crowddiff](https://github.com/dylran/crowddiff) |
| DDC | Diffuse-Denoise-Count（CVPRW 2023） | [arXiv:2303.12790](https://arxiv.org/abs/2303.12790) | [dylran/DiffuseDenoiseCount](https://github.com/dylran/DiffuseDenoiseCount) |
| Crowd-SAM | Crowd-SAM: SAM as a Smart Annotator（ECCV 2024） | [arXiv:2407.11464](https://arxiv.org/abs/2407.11464) | [FelixCaae/CrowdSAM](https://github.com/FelixCaae/CrowdSAM) |
| DGvGS | Domain Generalization via Gradient Surgery（ICCV 2021） | [arXiv:2108.01621](https://arxiv.org/abs/2108.01621) | [lucasmansilla/DGvGS](https://github.com/lucasmansilla/DGvGS) |
| CDCC | Leveraging Self-Supervision for Cross-Domain Crowd Counting（CVPR 2022 Oral） | [arXiv:2103.16291](https://arxiv.org/abs/2103.16291) | [weizheliu/Cross-Domain-Crowd-Counting](https://github.com/weizheliu/Cross-Domain-Crowd-Counting) |
| Switchable Whitening | Switchable Whitening for Deep Representation Learning（ICCV 2019） | [arXiv:1904.09739](https://arxiv.org/abs/1904.09739) | [XingangPan/Switchable-Whitening](https://github.com/XingangPan/Switchable-Whitening) |
| IBN-Net | Two at Once: IBN-Net（ECCV 2018） | [arXiv:1807.09441](https://arxiv.org/abs/1807.09441) | [XingangPan/IBN-Net](https://github.com/XingangPan/IBN-Net) |
| BIN | Batch-Instance Normalization（NeurIPS 2018） | [arXiv:1805.07925](https://arxiv.org/abs/1805.07925) | [hyseob/Batch-Instance-Normalization](https://github.com/hyseob/Batch-Instance-Normalization) |
| AdaSEEMCount | Robust Zero-Shot Crowd Counting and Localization with Adaptive Resolution SAM（ECCV 2024） | [arXiv:2402.17514](https://arxiv.org/abs/2402.17514) | [jia-wan/AdaSEEMCount_pytorch](https://github.com/jia-wan/AdaSEEMCount_pytorch) |
| LearningToCountAnything | Learning to Count Anything（arXiv 2022） | [arXiv:2205.10203](https://arxiv.org/abs/2205.10203) | [ActiveVisionLab/LearningToCountAnything](https://github.com/ActiveVisionLab/LearningToCountAnything) |

### 5.2 相关开源资源

| 资源 | 说明 | 链接 |
|---|---|---|
| CrowdCounting-framework-PyTorch | 基于 PyTorch 的人群计数统一框架，涵盖密度图回归与点回归两大类算法的多种实现（P2PNet、PET、Consistent-Point、P2RLoss、Uncertainty 等），并附可视化演示应用 | [KeepTryingTo/CrowdCounting-framework-PyTorch](https://github.com/KeepTryingTo/CrowdCounting-framework-PyTorch) |
| Awesome-Crowd-Counting | 人群计数论文清单（Awesome 系列，持续更新） | [gjy3035/Awesome-Crowd-Counting](https://github.com/gjy3035/Awesome-Crowd-Counting) |

---

## 六、论文讲解博客与视频（Keep_Trying_Go）

> **作者主页**：CSDN 博客 [blog.csdn.net/Keep_Trying_Go](https://blog.csdn.net/Keep_Trying_Go?spm=1010.2135.3001.10640)（1230 篇原创，含"论文讲解"专栏 160 篇）；Bilibili 视频空间 [space.bilibili.com/625095571](https://space.bilibili.com/625095571/upload/video)（"keep_trying_go"，含人群计数、SAM 分割、文生图等论文视频讲解）
> 以下为该作者针对本文所收录人群计数论文撰写的 **CSDN 博客详解** 与 **Bilibili 视频讲解** 对应关系（上文各论文表格中已同步内嵌这些链接）。

### 6.1 博客/视频与论文对应表

| 论文 | CSDN 博客详解 | Bilibili 视频讲解 |
|---|---|---|
| PET: Point-Query Quadtree for Crowd Counting, Localization, and More（ICCV 2023） | [PET人群计数论文方法与实验详解](https://blog.csdn.net/Keep_Trying_Go/article/details/170289534) | - |
| SAL: Boosting Semi-supervised Crowd Counting with Scale-based Active Learning（ACM MM 2024） | [SAL论文方法与实验详解](https://blog.csdn.net/Keep_Trying_Go/article/details/170289502) | [基于主动学习的半监督人群计数算法](https://www.bilibili.com/video/BV1hFJt61Ehg) |
| P2RLoss: Point-to-Region Loss for Semi-Supervised Point-Based Crowd Counting（CVPR 2025） | [P2RLoss论文方法与实验详解](https://blog.csdn.net/Keep_Trying_Go/article/details/170289436) | - |
| Consistent-Point: Consistent Pseudo-Points for Semi-Supervised Crowd Counting and Localization（arXiv 2025） | [Consistent-Point半监督人群计数算法详解](https://blog.csdn.net/Keep_Trying_Go/article/details/169744882) | [人群计数半监督算法一致点讲解](https://www.bilibili.com/video/BV1Lfxi6fEFU) |
| Calibrating Uncertainty for Semi-Supervised Crowd Counting（ICCV 2023） | [Uncertainty Semi-Supervised Crowd Counting人群计算算法](https://blog.csdn.net/Keep_Trying_Go/article/details/169653058) | - |
| Crowd-SAM: SAM as a Smart Annotator for Object Detection in Crowded Scenes（ECCV 2024） | [Crowd-SAM人群检测论文详解](https://blog.csdn.net/Keep_Trying_Go/article/details/168236939) | - |
| Exclusivity-Guided Mask Learning for Semi-Supervised Crowd Instance Segmentation and Counting（LNCS 2026） | [Exclusivity-Guided Mask Learning 论文详解](https://blog.csdn.net/Keep_Trying_Go/article/details/167130146) | - |
| Multi-modal Crowd Counting via a Broker Modality（ECCV 2024） | [基于多模态的人群统计算法详解](https://blog.csdn.net/Keep_Trying_Go/article/details/156830311) | - |
| URM: Single Domain Generalization for Few-Shot Counting via Universal Representation Matching（CVPR 2025） | [基于单域泛化的目标统计算法URM详解](https://blog.csdn.net/Keep_Trying_Go/article/details/156870771) | [基于单域泛化的目标统计URM算法详解【论文解读】](https://www.bilibili.com/video/BV16pDjBuE4r) |
| CrowdDiff: Multi-Hypothesis Crowd Density Estimation using Diffusion Models（CVPR 2024） | [基于扩散模型（diffusion Model）的人群计数方法（CrowdDiff）](https://blog.csdn.net/Keep_Trying_Go/article/details/157175412) | - |
| L2R: Leveraging Unlabeled Data for Crowd Counting by Learning to Rank（CVPR 2018） | [论文Leveraging Unlabeled Data for Crowd Counting by Learning to Rank算法详解](https://blog.csdn.net/Keep_Trying_Go/article/details/154913403) | - |
| STEERER: Resolving Scale Variations for Counting and Localization（ICCV 2023） | [论文STEERER人群计数，车辆计数以及农作物计数算法详解](https://blog.csdn.net/Keep_Trying_Go/article/details/154789450) | - |
| P2PNet: Rethinking Counting and Localization in Crowds（ICCV 2021） | [论文Rethinking Counting and Localization in Crowds: A Purely Point-Based Framework算法详解](https://blog.csdn.net/Keep_Trying_Go/article/details/154443638) | - |
| TMTB: Taste More, Taste Better（CVPR 2025） | [论文TMTB（Taste More, Taste Better）详解](https://blog.csdn.net/Keep_Trying_Go/article/details/148124251) | - |
| Robust Zero-Shot Crowd Counting and Localization With Adaptive Resolution SAM（ECCV 2024） | [论文Robust Zero-Shot Crowd Counting and Localization With Adaptive Resolution SAM讲解](https://blog.csdn.net/Keep_Trying_Go/article/details/148300284) | - |
| CSS-CCNN: Completely Self-Supervised Crowd Counting via Distribution Matching（TIP 2022） | [论文Completely Self-Supervised Crowd Counting via Distribution Matching无监督算法详解](https://blog.csdn.net/Keep_Trying_Go/article/details/148147162) | - |
| CrowdCLIP: Unsupervised Crowd Counting via Vision-Language Model（CVPR 2023） | [论文CrowdCLIP（基于CLIP的无监督人群计数模型）详解](https://blog.csdn.net/Keep_Trying_Go/article/details/147851355) | - |
| CLIP-EBC: CLIP Can Count Accurately through Enhanced Blockwise Classification（ICME 2025） | [论文CLIP-EBC（基于CLIP的人群统计模型）详解](https://blog.csdn.net/Keep_Trying_Go/article/details/147819012) | - |
| FFNet: The Effectiveness of a Simplified Model Structure for Crowd Counting（arXiv 2024） | [论文The Effectiveness of a Simplified Model Structure for Crowd Counting（FFNet）详解](https://blog.csdn.net/Keep_Trying_Go/article/details/141355068) | - |
| DM-Count: Distribution Matching for Crowd Counting（NeurIPS 2020） | [论文Distribution Matching for Crowd Counting详解](https://blog.csdn.net/Keep_Trying_Go/article/details/143133438)；[C Loss / OT Loss / TV Loss 损失详解](https://blog.csdn.net/Keep_Trying_Go/article/details/143219789) | - |
| DCCUS: Domain-general Crowd Counting in Unseen Scenarios（AAAI 2023） | [论文Domain-General Crowd Counting in Unseen Scenarios（DCCUS）详解以及对应代码详解](https://blog.csdn.net/Keep_Trying_Go/article/details/142730047) | - |

### 6.2 博客中讲解的其他计数相关论文（扩展阅读）

| 论文 | CSDN 博客详解 |
|---|---|
| CLIP-Count: Towards Text-Guided Zero-Shot Object Counting（ICCV 2023） | [论文CLIP-Count（基于文本指导的零样本目标计数）详解](https://blog.csdn.net/Keep_Trying_Go/article/details/147873916) |
| CounTR: Transformer-based Generalised Visual Counting（ECCV 2022） | [基于Transformer的目标统计方法（CounTR）](https://blog.csdn.net/Keep_Trying_Go/article/details/155421092) |
| T2ICount: Enhancing Cross-modal Understanding for Zero-Shot Counting（CVPR 2024） | [基于Zero-Shot的计数算法详解（T2ICount）](https://blog.csdn.net/Keep_Trying_Go/article/details/155243669) |
| Teaching CLIP to Count to Ten（ICCV 2023） | [Teaching CLIP to Count to Ten论文详解](https://blog.csdn.net/Keep_Trying_Go/article/details/155533000) |
| CountTX: Open-world Text-specified Object Counting（arXiv 2024） | [基于Zero-Shot的目标计数算法详解（Open-world Text-specified Object Counting）](https://blog.csdn.net/Keep_Trying_Go/article/details/155274695) |
| ZSC: Zero-shot Object Counting（CVPR 2023） | [基于zero-shot目标计数方法详解（Zero-Shot Object Counting）](https://blog.csdn.net/Keep_Trying_Go/article/details/155312948) |
| FastSAM（arXiv 2023，分割） | [分割算法FastSAM论文详解](https://blog.csdn.net/Keep_Trying_Go/article/details/167922125) |
| MobileSAM（NeurIPS 2023，分割） / MobileSAMv2（arXiv 2023） | [MobileSAM 论文方法详解](https://blog.csdn.net/Keep_Trying_Go/article/details/167223567)；[MobileSAMv2分割算法详解](https://blog.csdn.net/Keep_Trying_Go/article/details/167569383)（B 站视频：[MobileSAM](https://www.bilibili.com/video/BV1o1xX6kEjt)、[MobileSAMv2](https://www.bilibili.com/video/BV1RSW76KEKA)） |

### 6.3 相关学习资源文章

| 资源 | 链接 |
|---|---|
| 人群计数中常用数据集的总结以及使用方式（Python/PyTorch） | [CSDN](https://blog.csdn.net/Keep_Trying_Go/article/details/147144537) |
| Reference-less / Zero-shot / Few-shot Counting、单域泛化与域自适应概念辨析 | [CSDN](https://blog.csdn.net/Keep_Trying_Go/article/details/147893931) |
| PyTorch Lightning 教程（视频 + 文字） | [CSDN](https://blog.csdn.net/Keep_Trying_Go/article/details/148050185) |
| B 站视频空间（全部 18 个讲解视频，含文生图、SAM 分割、GLIGEN、SSA-GAN 等） | [space.bilibili.com/625095571/upload/video](https://space.bilibili.com/625095571/upload/video) |

---

> **统计**：共收录 **276 篇**去重后的论文（含综述、数据集论文及相关基础论文），覆盖 2008–2026 年；代码仓库 **31 个**（官方/非官方/复现）；Keep_Trying_Go 论文讲解博客 **22 篇**（对应 21 篇收录论文）+ Bilibili 视频讲解 **3 个**（另有 SAM/文生图等相关视频）。
> **更新日期**：2026-11-09
