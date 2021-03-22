# Awesome Self-supervised Representation Learning:
![Update](https://img.shields.io/github/last-commit/XinyuSun/awesome-self-supervised-representation-learning?color=green&label=last-updated&logo=update&style=flat-squre)

A curated list of self-supervised representation learning.

## Contents
- [Self-supervised Vedio Representation Learning](#svrl)
    - [Paper](#svrl-papers)
        - [2021](#svrl-2021) - [2020](#svrl-2020) - [2019](#svrl-2019)
    - [Datasets](#svrl-data)
    - [Benchmark Results](#svrl-result)
- [Self-supervised Visual Representation Learning](#sirl)
    - [Paper](#sirl-papers)
        - [2021](#sirl-2021) - [2020](#sirl-2020)
    - [Datasets](#sirl-data)
    - [Benchmark Results](#sirl-result)
- [Self-supervised Multi-modal Representation Learning](#smrl)
    - [Paper](#smrl-papers)
        - [2021](#smrl-2021) - [2020](#smrl-2020)
    - [Datasets](#smrl-data)
    - [Benchmark Results](#smrl-result)
---
## <span id="svrl"> **Self-supervised Vedio Representation Learning** </span>

## <span id="svrl-papers"> Papers </span>

### <span id="svrl-2021"> 2021 </span>
- <span id="svrl-p21-06">[[STS]](#svrl-r21-06)</span> [**Self-supervised Video Representation Learning by Uncovering Spatio-temporal Statistics**](https://arxiv.org/pdf/2008.13426) - Jiangliu Wang et al, `TPAMI 2021`
- <span id="svrl-p21-05">[[VideoMoCo]](#svrl-r21-05)</span> [**VideoMoCo: Contrastive Video Representation Learning with Temporally Adversarial Examples**](https://arxiv.org/pdf/2103.05905) - Tian Pan et al, `CVPR 2021`
- <span id="svrl-p21-04">[[BE]](#svrl-r21-04)</span> [**Removing the Background by Adding the Background: Towards Background Robust Self-supervised Video Representation Learning**](https://arxiv.org/pdf/2009.05769.pdf) - Jinpeng Wang et al, `CVPR 2021`
- <span id="svrl-p21-03">[[RSPNet]](#svrl-r21-03)</span> [**RSPNet: Relative Speed Perception for Unsupervised Video Representation Learning**](https://arxiv.org/pdf/2011.07949v2) - Peihao Chen et al, `AAAI 2021`
- <span id="svrl-p21-02">[[DSM]](#svrl-r21-02)</span> [**Enhancing Unsupervised Video Representation Learning by Decoupling the Scene and the Motion**](https://arxiv.org/pdf/2009.05757.pdf) - Jinpeng Wang et al, `AAAI 2021`
- <span id="svrl-p21-01">[[TCLR]](#svrl-r21-01)</span> [**TCLR: Temporal Contrastive Learning for Video Representation**](https://arxiv.org/pdf/2101.07974v2) - Ishan Dave et al, `Arxiv 2021`

### <span id="svrl-2020"> 2020 </span>
- <span id="svrl-p20-15">[[CCL]](#svrl-r20-15)</span> [**Cycle-Contrast for Self-Supervised Video Representation Learning**](https://proceedings.neurips.cc/paper/2020/file/5c9452254bccd24b8ad0bb1ab4408ad1-Paper.pdf) - Quan Kong et al, `NeurIPS 2020`
- <span id="svrl-p20-14">[[CoCLR]](#svrl-r20-14)</span> [**Self-supervised Co-training for Video Representation Learning**](https://proceedings.neurips.cc/paper/2020/file/3def184ad8f4755ff269862ea77393dd-Paper.pdf) - Tengda Han et al, `NeurIPS 2020`
- <span id="svrl-p20-13">[[PRP]](#svrl-r20-13)</span> [**Video Playback Rate Perception for Self-Supervised Spatio-Temporal Representation Learning**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yao_Video_Playback_Rate_Perception_for_Self-Supervised_Spatio-Temporal_Representation_Learning_CVPR_2020_paper.pdf) - Yuan Yao et al, `CVPR 2020`
- <span id="svrl-p20-12">[[VRE-MRA]](#svrl-r20-12)</span> [**Exploiting Motion Information from Unlabeled Videos for Static Image Action Recognition**](https://arxiv.org/pdf/1912.00308.pdf) - Yiyi Zhang et al, `AAAI 2020`
- <span id="svrl-p20-11">[[VCP]](#svrl-r20-11)</span> [**Video Cloze Procedure for Self-Supervised Spatio-Temporal Learning**](https://arxiv.org/pdf/2001.00294v1) - Dezhao Luo et al, `AAAI 2020`
- <span id="svrl-p20-10">[[IIC]](#svrl-r20-10)</span> [**Self-supervised Video Representation Learning Using Inter-intra Contrastive Framework**](https://arxiv.org/pdf/2008.02531) - Li Tao et al, `ACMMM 2020`
- <span id="svrl-p20-09">[[RTT]](#svrl-r20-09)</span> [**Video Representation Learning by Recognizing Temporal Transformations**](https://arxiv.org/pdf/2007.10730.pdf) - Simon Jenni et al, `ECCV 2020`
- <span id="svrl-p20-08">[[VPP]](#svrl-r20-08)</span> [**Self-Supervised Video Representation Learning by Pace Prediction**](https://arxiv.org/pdf/2008.05861) - Jiangliu Wang et al, `ECCV 2020`
- <span id="svrl-p20-07">[[DTG-Net]](#svrl-r20-07)</span> [**DTG-Net: Differentiated Teachers Guided Self-Supervised Video Action Recognition**](https://arxiv.org/pdf/2006.07609) - Ziming Liu et al, `Arxiv 2020`
- <span id="svrl-p20-06">[[VTDL]](#svrl-r20-06)</span> [**Self-supervised Temporal Discriminative Learning for Video Representation Learning**](https://arxiv.org/pdf/2008.02129) - Jinpeng Wang et al, `Arxiv 2020`
- <span id="svrl-p20-05">[[CVRL]](#svrl-r20-05)</span> [**Spatiotemporal Contrastive Video Representation Learning**](https://arxiv.org/pdf/2008.03800v3) - Rui Qian et al, `Arxiv 2020`
- <span id="svrl-p20-04">[[PCL]](#svrl-r20-04)</span> [**Self-Supervised Video Representation Using Pretext-Contrastive Learning**](https://arxiv.org/pdf/2010.15464v1) - Li Tao et al, `Arxiv 2020`
- <span id="svrl-p20-03">[[TCE]](#svrl-r20-03)</span> [**Temporally Coherent Embeddings for Self-Supervised Video Representation Learning**](https://arxiv.org/pdf/2004.02753v5) - Joshua Knights et al, `Arxiv 2020`
- <span id="svrl-p20-02">[[HDC]](#svrl-r20-02)</span> [**Hierarchically Decoupled Spatial-Temporal Contrast for Self-supervised Video Representation Learning**](https://arxiv.org/pdf/2011.11261) - Zehua Zhang et al, `Arxiv 2020`
- <span id="svrl-p20-01">[[CEP]](#svrl-r20-01)</span> [**Back to the Future: Cycle Encoding Prediction for Self-supervised Contrastive Video Representation Learning**](https://arxiv.org/pdf/2010.07217) - Xinyu Yang et al, `Arxiv 2020`


- [[TaCo]]() [**Can Temporal Information Help with Contrastive Self-Supervised Learning?**](https://arxiv.org/pdf/2011.13046.pdf) - Yutong Bai et al, `Arxiv 2020`

### <span id="svrl-2019"> 2019 </span>
- <span id="svrl-p19-01">[[DPC]](#svrl-r19-01)</span> [**Video Representation Learning by Dense Predictive Coding**](https://arxiv.org/pdf/1909.04656v3) - Tengda Han et al, `ICCV Workshops 2019`

### Others
- [[]]() [**Space-Time Correspondence as a Contrastive Random Walk**](https://arxiv.org/pdf/2006.14613) - Allan Jabri et al, `NeurIPS 2020`
- [[]]() [**Exploiting Temporal Coherence for Self-Supervised One-shot Video Re-identification**](https://arxiv.org/pdf/2007.11064) - Dripta S. Raychaudhuri et al, `ECCV 2020`
- [[]]() [**Self-Supervision by Prediction for Object Discovery in Videos**](https://arxiv.org/pdf/2103.05669) - Beril Besbinar et al, `Arxiv 2021`

## <span id="svrl-data"> Datasets </span>
- UCF101
- HMDB51

## <span id="svrl-result"> Benchmark Results </span>
#### <span id = "svrl-result-ucf101"> UCF101 & HMDB51 </span>
|                         Method                          |  Conference   |   Network   |   Input size   |   Pretrain Dataset   |  UCF101 Acc.(%)  | HMDB51 Acc.(%) |
| :-----------------------------------------------------: | :-----------: | :---------: | :------------: | :------------------: | :--------------: | :------------: |
| <span id="svrl-r21-01">[[TCLR]](#svrl-p21-01)</span>    |   Arxiv 2021  |   R(2+1)D   |     112x112    |      Kinetic-400     |    ***84.3***    |   ***54.2***   |
|                                                         |               |     R3D     |     112x112    |      Kinetic-400     |       84.1       |      53.6      |
| <span id="svrl-r21-02">[[DSM]](#svrl-p21-02)</span>     |   AAAI 2021   |    R3D-34   |     224x224    |      Kinetic-400     |    ***78.2***    |   ***52.8***   |
|                                                         |               |     I3D     |     224x224    |      Kinetic-400     |       74.8       |      52.5      |
| <span id="svrl-r21-03">[[RSPNet]](#svrl-p21-03)</span>  |   AAAI 2021   |    S3D-G    |     112x112    |      Kinetic-400     |    ***93.7***    |   ***64.7***   |
|                                                         |               |   R(2+1)D   |     112x112    |      Kinetic-400     |       81.1       |      44.6      |
|                                                         |               |     C3D     |     112x112    |      Kinetic-400     |       76.7       |      44.6      |
|                                                         |               |     R3D     |     112x112    |      Kinetic-400     |       74.3       |      41.8      |
| <span id="svrl-r21-04">[[BE]](#svrl-p21-04)</span>      |   CVPR 2021   |     R3D     |     224x224    |      Kinetic-400     |    ***87.1***    |   ***56.2***   |
|                                                         |               |     I3D     |     224x224    |      Kinetic-400     |       86.8       |      55.4      |
| <span id="svrl-r21-05">[[VMoCo]](#svrl-p21-05)</span>   |   CVPR 2021   |   R(2+1)D   |     112x112    |      Kinetic-400     |    ***78.7***    |   ***49.2***   |
|                                                         |               |     R3D     |     112x112    |      Kinetic-400     |       74.1       |      43.6      |
| <span id="svrl-r21-06">[[STS]](#svrl-p21-06)</span>     |   TPAMI 2021  |    S3D-G    |     224x224    |      Kinetic-400     |    ***89.0***    |   ***62.0***   |
| <span id="svrl-r20-01">[[CEP]](#svrl-p20-01)</span>     |   Arxiv 2020  |   R(2+1)D   |     224x224    |      Kinetic-400     |    ***76.3***    |   ***36.8***   |
|                                                         |               |  SlowFast   |     128x128    |      Kinetic-400     |       68.5       |      36.8      |
| <span id="svrl-r20-02">[[HDC]](#svrl-p20-02)</span>     |   Arxiv 2020  |   R(2+1)D   |     112x112    |      Kinetic-400     |    ***76.2***    |   ***39.8***   |
|                                                         |               |     C3D     |     112x112    |      Kinetic-400     |       72.3       |      39.3      |
|                                                         |               |     R3D     |     112x112    |      Kinetic-400     |       68.5       |      38.1      |
| <span id="svrl-r20-03">[[TCE]](#svrl-p20-03)</span>     |   Arxiv 2020  |    R2D-50   |     224x224    |      Kinetic-400     |    ***71.2***    |   ***36.6***   |
|                                                         |               |    R2D-18   |     224x224    |      Kinetic-400     |       68.8       |      34.2      |
| <span id="svrl-r20-04">[[PCL]](#svrl-p20-04)</span>     |   Arxiv 2020  |     R3D     |     112x112    |      Kinetic-400     |    ***82.3***    |   ***43.2***   |
|                                                         |               |   R(2+1)D   |     112x112    |      Kinetic-400     |       80.7       |      44.6      |
|                                                         |               |     C3D     |     112x112    |      Kinetic-400     |       79.7       |      42.3      |
|                                                         |               |     R3D     |     112x112    |      Kinetic-400     |       79.5       |      41.7      |
| <span id="svrl-r20-05">[[CVRL]](#svrl-p20-05)</span>    |   Arxiv 2020  |   R3D-101   |     224x224    |      Kinetic-600     |    ***93.6***    |   ***69.4***   |
|                                                         |               |   R3D-101   |     224x224    |      Kinetic-400     |       92.9       |      66.7      |
| <span id="svrl-r20-06">[[VTDL]](#svrl-p20-06)</span>    |   Arxiv 2020  |   R(2+1)D   |     224x224    |      Kinetic-400     |    ***84.9***    |   ***52.5***   |
|                                                         |               |     I3D     |     224x224    |      Kinetic-400     |       82.1       |      52.9      |
|                                                         |               |     R3D     |     224x224    |      Kinetic-400     |       78.4       |      49.1      |
| <span id="svrl-r20-07">[[DTG-Net]](#svrl-p20-07)</span> |   Arxiv 2020  |TSN-ResNet18 |        -       |      Kinetic-400     |    ***69.1***    |       -        |
| <span id="svrl-r20-08">[[VPP]](#svrl-p20-08)</span>     |   Arxiv 2020  |   R(2+1)D   |     224x224    |      Kinetic-400     |    ***77.1***    |   ***36.6***   |
| <span id="svrl-r20-09">[[RTT]](#svrl-p20-09)</span>     |   ECCV 2020   |     R3D     |     112x112    |      Kinetic-400     |    ***79.3***    |   ***49.8***   |
|                                                         |               |     C3D     |     112x112    |      Kinetic-400     |       69.9       |      39.6      |


## <span id="sirl"> **Self-supervised Visual Representation Learning** </span>

## <span id="sirl-papers"> Papers </span>

### <span id="sirl-2021"> 2021 </span>
- [[]]() [**Context Matters: Graph-based Self-supervised Representation Learning for Medical Images**](https://arxiv.org/pdf/2012.06457) - Li Sun et al, `AAAI 2021`

### <span id="sirl-2020"> 2020 </span>
- [[]]() [**CompRess: Self-Supervised Learning by Compressing Representations**](https://proceedings.neurips.cc/paper/2020/file/975a1c8b9aee1c48d32e13ec30be7905-Paper.pdf) - Soroush Abbasi Koohpayegani et al, `NeurIPS 2020`
- [[]]() [**Self-Supervised Visual Representation Learning from Hierarchical Grouping**](https://proceedings.neurips.cc/paper/2020/file/c1502ae5a4d514baec129f72948c266e-Paper.pdf) - Xiao Zhang et al, `NeurIPS 2020`
- [[BYOL]]() [**Bootstrap Your Own Latent - A New Approach to Self-Supervised Learning**](https://proceedings.neurips.cc/paper/2020/file/f3ada80d5c4ee70142b17b8192b2958e-Paper.pdf) - Jean-Bastien Grill et al, `NeurIPS 2020`

## <span id="smrl"> **Self-supervised Multi-modal Representation Learning** </span>

## <span id="smrl-papers"> Papers </span>

### <span id="smrl-2021"> 2021 </span>
- [**Enhancing Audio-Visual Association with Self-Supervised Curriculum Learning**](https://www.aaai.org/AAAI21Papers/AAAI-6067.ZhangJ.pdf) - Jingran Zhang et al, `AAAI 2021`

### <span id="smrl-2020"> 2020 </span>
- [**Self-Supervised Learning by Cross-Modal Audio-Video Clustering**](https://arxiv.org/pdf/1911.12667v3) - Humam Alwassel et al, `NeurIPS 2020`
- [**Self-Supervised MultiModal Versatile Networks**](https://arxiv.org/pdf/2006.16228v2) - Jean-Baptiste Alayrac et al, `NeurIPS 2020`
- [**Labelling unlabelled videos from scratch with multi-modal self-supervision**](https://proceedings.neurips.cc/paper/2020/file/31fefc0e570cb3860f2a6d4b38c6490d-Paper.pdf) - Yuki Asano et al, `NeurIPS 2020`
- [[AVSA]]() [**Learning Representations from Audio-Visual Spatial Alignment**](https://proceedings.neurips.cc/paper/2020/file/328e5d4c166bb340b314d457a208dc83-Paper.pdf) - Pedro Morgado et al, `NeurIPS 2020`
- [[ELO]]() [**Evolving Losses for Unsupervised Video Representation Learning**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Piergiovanni_Evolving_Losses_for_Unsupervised_Video_Representation_Learning_CVPR_2020_paper.pdf) - AJ Piergiovanni et al, `CVPR 2020`
- [**Audio-Visual Instance Discrimination with Cross-Modal Agreement**](https://arxiv.org/pdf/2004.12943v2) - Pedro Morgado et al, `Arxiv 2020`