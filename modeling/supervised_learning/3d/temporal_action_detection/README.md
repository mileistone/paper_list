### Single-Stage

#### Detection-based

##### 2021
- [2101.08540] [Activity Graph Transformer for Temporal Action Localization](https://arxiv.org/abs/2101.08540)
  - extract features via pre-trained temporal action recognition model
    - two-stream
  - one-stage
  - RGB + optical flow
    - early fusion
      - concatenate
##### 2020
- [CVPR2020] [G-TAD: Sub-Graph Localization for Temporal Action Detection](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xu_G-TAD_Sub-Graph_Localization_for_Temporal_Action_Detection_CVPR_2020_paper.pdf)
  - extract features via pre-trained temporal action recognition model
- [TIP2020] [Revisiting Anchor Mechanisms for Temporal Action Localization](https://arxiv.org/abs/2008.09837)
  - propose a novel anchor-free action localization module
  - combine anchor-free module and anchor-based module
  - extract features via pre-trained temporal action recognition model
    - two-stream
  - one-stage
  - RGB + optical flow
    - early fusion
      - concatenate
- [MM2020] [Deep Concept-wise Temporal Convolutional Networks for Action Localization](https://arxiv.org/abs/1908.09442)
  - concept-wise temporal convolutional network
    - depth-wise conv + parameter sharing
  - extract features via pre-trained temporal action recognition model
    - two-stream
  - one-stage
  - RGB + optical flow
    - early fusion
      - concatenate
  - anchor-based
- [ICME2020] [Scale Matters: Temporal Scale Aggregation Network for Precise Action Localization in Untrimmed Videos](https://arxiv.org/abs/1908.00707)
  - Adapt ASPP to Temporal Action Localization
- [PRCV2020] [Multi-Level Temporal Pyramid Network for Action Detection](https://arxiv.org/abs/2008.03270)
  - extract features via pre-trained temporal action recognition model
    - two-stream
  - one-stage
  - RGB + optical flow
    - early fusion
      - concatenate
- [2006.07526] [CBR-Net: Cascade Boundary Refinement Network for Action Detection: Submission to ActivityNet Challenge 2020](https://arxiv.org/abs/2006.07526v2)

##### 2019
- [CVPR2019] [Gaussian Temporal Awareness Networks for Action Localization](http://openaccess.thecvf.com/content_CVPR_2019/papers/Long_Gaussian_Temporal_Awareness_Networks_for_Action_Localization_CVPR_2019_paper.pdf)
- [AAAI2019] [Video Imprint Segmentation for Temporal Action Detection in Untrimmed Videos](https://ojs.aaai.org//index.php/AAAI/article/view/4846)
- [1910.08250] [AFO-TAD: Anchor-free One-Stage Detector for Temporal Action Detection](https://arxiv.org/abs/1910.08250)

##### 2018
- [BMVC2018] [S3D: Single Shot multi-Span Detector via Fully 3D Convolutional Networks](https://arxiv.org/abs/1807.08069)
  - present a novel Single Shot multi-Span Detector for temporal activity detection using a simple end-to-end fully three-dimensional convolutional network
  - one-stage

##### 2017
- [BMVC2017] [End-to-End, Single-Stream Temporal Action Detection in Untrimmed Videos](http://vision.stanford.edu/pdf/buch2017bmvc.pdf)
- [MM2017] [Single Shot Temporal Action Detection](https://arxiv.org/abs/1710.06236)

#### Segmentation-based
- [1608.08128] [Temporal Activity Detection in Untrimmed Videos with Recurrent Neural Networks](https://arxiv.org/abs/1608.08128)
- [THUMOS14 submission] [Action Recognition and Detection by Combining Motion and Appearance Features](http://crcv.ucf.edu/THUMOS14/papers/CUHK&SIAT.pdf)
- [THUMOS14 submission] [The LEAR Submission at Thumos 2014](https://hal.inria.fr/hal-01074442/document)

### Multi-Stage
#### Proposal Generation
##### 2021
- [CVPR2021] [Temporal Context Aggregation Network for Temporal Action Proposal Refinement](https://arxiv.org/abs/2103.13141)
  - extract features via pre-trained temporal action recognition model
    - two-stream
  - RGB + optical flow
- [AAAI2021] [BSN++: Complementary Boundary Regressor with Scale-Balanced Relation Modeling for Temporal Action Proposal Generation](https://arxiv.org/abs/2009.07641)

##### 2020
- [ECCV2020] [Bottom-Up Temporal Action Localization with Mutual Regularization](https://arxiv.org/abs/2002.07358)
  - extract features via pre-trained temporal action recognition model
    - two-stream
  - RGB + optical flow
- [ECCV2020] [Boundary Content Graph Neural Network for Temporal Action Proposal Generation](https://arxiv.org/abs/2008.01432)
- [AAAI2020] [Accurate Temporal Action Proposal Generation with Relation-Aware Pyramid Network](https://arxiv.org/abs/2003.04145)
- [AAAI2020] [Fast Learning of Temporal Action Proposal via Dense Boundary Generator](https://arxiv.org/abs/1911.04127)

##### 2019
- [ICCV2019] [BMN: Boundary-Matching Network for Temporal Action Proposal Generation](https://arxiv.org/abs/1907.09702)
- [ICCV2019] [Graph Convolutional Networks for Temporal Action Localization](https://arxiv.org/abs/1909.03252)
  - extract features via pre-trained temporal action recognition model
    - two-stream
  - RGB + optical flow
- [CVPR2019] [Multi-granularity Generator for Temporal Action Proposal](https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Multi-Granularity_Generator_for_Temporal_Action_Proposal_CVPR_2019_paper.pdf)

##### 2018
- [ECCV2018] [BSN: Boundary Sensitive Network for Temporal Action Proposal Generation](https://arxiv.org/abs/1806.02964)
- [ECCV2018] [CTAP: Complementary Temporal Action Proposal Generation](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Jiyang_Gao_CTAP_Complementary_Temporal_ECCV_2018_paper.pdf)

##### Detection
##### 2021
- [CVPR2021] [Learning Salient Boundary Feature for Anchor-free Temporal Action Localization](https://arxiv.org/abs/2103.13137)
  - propose the first purely anchor-free temporal localization method
  - RGB + optical flow
    - late fusion
      - average location and classification score

##### 2020
- [AAAI2020] [Progressive Boundary Refinement Network for Temporal Action Detection](https://ojs.aaai.org//index.php/AAAI/article/view/6829)
  - RGB + optical flow
    - late fusion
      - average location and classification score

##### 2018
- [CVPR2018] [Rethinking the Faster R-CNN Architecture for Temporal Action Localization](https://arxiv.org/abs/1804.07667)
  - extract features via pre-trained temporal action recognition model
    - two-stream
  - RGB + optical flow
   
##### 2017
- [ICCV2017] [R-C3D: Region Convolutional 3D Network for Temporal Activity Detection](https://arxiv.org/abs/1703.07814)


