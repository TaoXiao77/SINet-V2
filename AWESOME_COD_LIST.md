<p align="center">
    <img src="./imgs/COD-Logo.png"/> <br />
</p>

# <p align=center>`Awesome List for Camouflaged Object Detection (COD)`

![Badge](https://img.shields.io/badge/-As%20awesome%20as%20you%20think!-red)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/GewelsJI/SINet-V2)
![GitHub issues](https://img.shields.io/github/issues/GewelsJI/SINet-V2)
![GitHub stars](https://img.shields.io/github/stars/GewelsJI/SINet-V2)

This awesome list is under construction. If you have anything to recommend or any suggestions, please feel free to contact us via e-mail (gepengai.ji@gmail) or directly push a PR. 

< **Last updated: Nov/12/2022** >


##  1. <a name='Content'></a>Content

<!-- vscode-markdown-toc -->
* 1. [Content](#Content)
* 2. [Paper List](#PaperList)
	* 2.1. [Datasets & Benchmarks](#DatasetsBenchmarks)
		* 2.1.1. [Video-level COD](#Video-levelCOD)
		* 2.1.2. [Image-level COD](#Image-levelCOD)
	* 2.2. [Camouflaged Object Detection (COD)](#CamouflagedObjectDetectionCOD)
		* 2.2.1. [YEAR 2023](#YEAR2023)
		* 2.2.2. [YEAR 2022](#YEAR2022)
		* 2.2.3. [YEAR 2021](#YEAR2021)
		* 2.2.4. [Before YEAR 2020](#BeforeYEAR2020)
	* 2.3. [Camouflaged Instance Segmentation (CIS)](#CamouflagedInstanceSegmentationCIS)
	* 2.4. [Video Camouflaged Object Detection (VCOD)](#VideoCamouflagedObjectDetectionVCOD)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->


##  2. <a name='PaperList'></a>Paper List

###  2.1. <a name='DatasetsBenchmarks'></a>Datasets & Benchmarks

####  2.1.1. <a name='Video-levelCOD'></a>Video-level COD

| **Dataset Name** | **Year** | **Publication** | **Links** |
| :------: | :------: | :-------: | :---------|
[MoCA-Mask](https://xueliancheng.github.io/SLT-Net-project/) | 2022 | CVPR | [Paper](https://arxiv.org/abs/2203.07363) |
[MoCA](https://www.robots.ox.ac.uk/~vgg/data/MoCA/) | 2020 | ACCV | [Paper](https://openaccess.thecvf.com/content/ACCV2020/html/Lamdouar_Betrayed_by_Motion_Camouflaged_Object_Discovery_via_Motion_Segmentation_ACCV_2020_paper.html) |


####  2.1.2. <a name='Image-levelCOD'></a>Image-level COD

| **Dataset Name** | **Year** | **Publication** | **Links** |
| :------: | :------: | :-------: | :---------|
[NC4K](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment) | 2021 | CVPR | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf) |
[COD10K](http://dpfan.net/camouflage/) | 2020 | CVPR | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf) |
[CAMO](https://sites.google.com/view/ltnghia/research/camo) | 2019 | CVIU | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf) |
[CPD1K](https://github.com/xfflyer/Camouflaged-people-detection) | 2019 | SPL | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8336933&casa_token=h25eiro16rcAAAAA:qeSoquItkaBK8QKGFvbiX2DJA0MycSjJ-5nK-2y0QSGxQY97b8b6BsLmoo8QJCQVD3HYPstW&tag=1) | 
[CHAMELEON](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) | 2017 | Online | [Website](https://www.polsl.pl/rau6/chameleon-database-animal-camouflage-analysis/) |


###  2.2. <a name='CamouflagedObjectDetectionCOD'></a>Camouflaged Object Detection (COD)


####  2.2.1. <a name='YEAR2023'></a>YEAR 2023

| **Year** | **Publication** | **Title**                                                    |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
| 2023  | MIR   | **Deep Gradient Learning for Efficient Camouflaged Object Detection** (`DGNet model`) <br><sup><sub>*Ge-Peng Ji, Deng-Ping Fan, Yu-Cheng Chou, Dengxin Dai, Alexander Liniger, Luc Van Gool*</sub></sup>  | [Paper](https://arxiv.org/abs/2205.12853v2)/[Code](https://github.com/GewelsJI/DGNet)

####  2.2.2. <a name='YEAR2022'></a>YEAR 2022

| **Year** | **Publication** | **Title**                                                    |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   2022   |   TPAMI   | **Concealed Object Detection** (`SINetV2 model & COD10K dataset`)                       <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Ming-Ming Cheng, Ling Shao*</sub></sup>                             | [Paper](https://arxiv.org/abs/2102.10274)/[Code](https://github.com/GewelsJI/SINet-V2)  
|   2022   |  arXiv   | **Boundary-Aware Segmentation Network for Mobile and Web Applications** (`BAS model`) <br> <sup><sub>*Xuebin Qin, Deng-Ping Fan, Chenyang Huang, et al.*</sub></sup> | [Paper](https://arxiv.org/pdf/2101.04704.pdf)/[Code](https://github.com/xuebinqin/BASNet) 
| 2022     | arXiv | Towards Deeper Understanding of Camouflaged Object Detection (`LSR extension`) <br> <sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2205.11333)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)
|   2022   |  arXiv   | High-resolution Iterative Feedback Network for Camouflaged Object Detection <br> <sup><sub>*Xiaobin Hu, Deng-Ping Fan, Xuebin Qin, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2203.11624)/[Code](https://github.com/HUuxiaobin/HitNet) 
|   2022   |  arXiv   | Transformer transforms salient object detection and camouflaged object detection <br> <sup><sub>*Yuxin Mao, Jing Zhang, Yuchao Dai, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2104.10127)/[Code](https://github.com/fupiao1998/TrasformerSOD)
|   2022   |   ACM MM     | PreyNet: Preying on camouflaged objects <br> <sup><sub>*M Zhang, S Xu, Yongri Piao, D Shi, S Lin, H Lu*</sub></sup> | [Paper](https://dl.acm.org/doi/abs/10.1145/3503161.3548178)/[Code](https://github.com/sxu1997/PreyNet)
|   2022   |  IJCAI   | Boundary-Guided Camouflaged Object Detection <br> <sup><sub>*Yujia Sun, Shuo Wang, Chenglizhao Chen, Tian-Zhu Xiang*</sub></sup> | [Paper](https://www.ijcai.org/proceedings/2022/186)/[Code](https://github.com/thograce/BGNet)
|   2022   |   CVPR   | Segment, Magnify and Reiterate: Detecting Camouflaged Objects the Hard Way <br> <sup><sub>*Qi Jia, S. Yao, Yu Liu, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Jia_Segment_Magnify_and_Reiterate_Detecting_Camouflaged_Objects_the_Hard_Way_CVPR_2022_paper.pdf)/[Code](https://github.com/dlut-dimt/SegMaR) 
|   2022   |   CVPR   | Detecting Camouflaged Object in Frequency Domain <br> <sup><sub>*Yijie Zhong, Bo Li, Lv Tang, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_Detecting_Camouflaged_Object_in_Frequency_Domain_CVPR_2022_paper.pdf)/Code
|   2022   |   CVPR   | Zoom In and Out: A Mixed-scale Triplet Network for Camouflaged Object Detection <br> <sup><sub>*Youwei Pang, Xiaoqi Zhao, Tian-Zhu Xiang, Lihe Zhang, Huchuan Lu*</sub></sup> | [Paper](https://arxiv.org/abs/2203.02688)/[Code](https://github.com/lartpang/ZoomNet) |
|   2022   |  AAAI    | I can find you! Boundary-guided Separated Attention Network for Camouflaged Object Detection <br><sup><sub>*Hongwei Zhu, Peng Li, Haoran Xie, Mingqiang Wei, et al.*</sub></sup> | [Paper](https://www.aaai.org/AAAI22Papers/AAAI-6565.ZhuH.pdf)/[Code](https://github.com/WolfberryCoke/BSA-Net) | 
|   2022   |  WACV    | Modeling Aleatoric Uncertainty for Camouflaged Object Detection <br> <sup><sub>*Jiawei Liu, Jing Zhang, Nick Barnes*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/WACV2022/papers/Liu_Modeling_Aleatoric_Uncertainty_for_Camouflaged_Object_Detection_WACV_2022_paper.pdf)/[Code](https://github.com/Carlisle-Liu/OCENet)
|   2022   | TCSVT | Camouflaged Object Detection via Context-aware Cross-level Fusion (`C2FNet Extension`)  <br> <sup><sub>*Geng Chen, Si-Jie Liu, Yu-Jia Sun, Ge-Peng Ji, Ya-Feng Wu, Tao Zhou*</sub></sup>  | [Paper](https://arxiv.org/abs/2207.13362)/[Code](https://github.com/Ben57882/C2FNet-TSCVT)
|   2022   |  TMM  | Deep Texton-Coherence Network for Camouflaged Object Detection <br> <sup><sub>*Wei Zhai, Yang Cao, HaiYong Xie, Zheng-Jun Zha*</sub></sup> | [Paper](https://ieeexplore.ieee.org/abstract/document/9815160)/Code
|   2022   |  KBS     | Boundary-guided network for camouflage object detection <br> <sup><sub>*Tianyou Chen, Jin Xiao, Xiaoguang Hu, Guofeng Zhang, Shaojie Wang*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705122004294)/[Code](https://github.com/clelouch/BgNet)
|   2022   |  PR      | CubeNet: X-shape connection for camouflaged object detection <br> <sup><sub>*Mingchen Zhuge, Xiankai Lu, Yiyou Guo, Zhihua Cai, Shuhan Chen*</sub></sup> | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S003132032200125X?dgcid=raven_sd_recommender_email)/[Code](https://github.com/mczhuge/CubeNet)
|   2022   |  PR      | Fast Camouflaged Object Detection via Edge-based Reversible Re-calibration Network <br><sup><sub>*Ge-Peng Ji, Lei Zhu, Mingchen Zhuge, Keren Fu*</sub></sup> | [Paper](https://arxiv.org/abs/2111.03216)/[Code](https://github.com/GewelsJI/ERRNet) 
|   2022   |  TOMM | Frequency-aware Camouflaged Object Detection <br> <sup><sub>*Jiaying Lin, Xin Tan, Ke Xu, Lizhuang Ma, Rynson W.H. Lau*</sub></sup> | [Paper](https://dl.acm.org/doi/abs/10.1145/3545609)/Code 
| 2022  | arXiv | Weakly-Supervised Camouflaged Object Detection with Scribble Annotations <br><sup><sub>*Ruozhen He, Qihua Dong, Jiaying Lin, Rynson W.H. Lau*</sub></sup> | [Paper](https://arxiv.org/abs/2207.14083)


####  2.2.3. <a name='YEAR2021'></a>YEAR 2021

| **Year** | **Publication** | **Title**                                                    |  **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   2021   |   ICCV   | Uncertainty-Guided Transformer Reasoning for Camouflaged Object Detection <br><sup><sub>*Fan Yang, Qiang Zhai, Xin Li, Rui Huang, et al.*</sub></sup>                                 | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Uncertainty-Guided_Transformer_Reasoning_for_Camouflaged_Object_Detection_ICCV_2021_paper.pdf)/[Code](https://github.com/fanyang587/UGTR)                                                   |
|   2021   |   CVPR   | Uncertainty-aware Joint Salient Object and Camouflaged Object Detection <br><sup><sub>*Aixuan Li, Jing Zhang, Yunqiu Lv, Bowen Liu, Tong Zhang, Yuchao Dai*</sub></sup>                     | [Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Li_Uncertainty-Aware_Joint_Salient_Object_and_Camouflaged_Object_Detection_CVPR_2021_paper.html)/[Code](https://github.com/JingZhang617/Joint_COD_SOD) |
|   2021   |   CVPR   | Simultaneously Localize, Segment and Rank the Camouflaged Objects (`NC4K`)  <br><sup><sub>*Yunqiu Lv, Jing Zhang, Yuchao Dai, Aixuan Li, et al.*</sub></sup>                                 | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Lv_Simultaneously_Localize_Segment_and_Rank_the_Camouflaged_Objects_CVPR_2021_paper.pdf)/[Code](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment)                                                   |
|   2021   |   CVPR   | Mutual Graph Learning for Camouflaged Object Detection       <br><sup><sub>*Qiang Zhai, Xin Li, Fan Yang, Chenglizhao Chen, Hong Cheng, Deng-Ping Fan*</sub></sup>                                   | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhai_Mutual_Graph_Learning_for_Camouflaged_Object_Detection_CVPR_2021_paper.pdf)/[Code](https://github.com/fanyang587/MGL)                                                   |
|   2021   |   CVPR   | Camouflaged Object Segmentation with Distraction Mining      <br><sup><sub>*Haiyang Mei, Ge-Peng Ji, Ziqi Wei, Xin Yang, Xiaopeng Wei, Deng-Ping Fan*</sub></sup>                               | [Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Mei_Camouflaged_Object_Segmentation_With_Distraction_Mining_CVPR_2021_paper.pdf)/[Code](https://mhaiyang.github.io/CVPR2021_PFNet/index)                                                   |
|   2021   |  IJCAI   | Context-aware Cross-level Fusion Network for Camouflaged Object Detection <br><sup><sub>*Yujia Sun, Geng Chen, Tao Zhou, Yi Zhang, Nian Liu*</sub></sup>                                  | [Paper](https://arxiv.org/abs/2105.12555)/[Code](https://github.com/thograce/C2FNet) |
|   2021   |   AAAI   | Inferring Camouflaged Objects by Texture-Aware Interactive Guidance Network <br><sup><sub>*Jinchao Zhu, Xiaoyu Zhang, Shuo Zhang, Junnan Liu*</sub></sup>                                           | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/16475)/Code |
| 2021 | arXiv | CamouFinder: Finding Camouflaged Instances in Images <br><sup><sub>*Trung-Nghia Le, Vuong Nguyen, Cong Le, et al.*</sub></sup> | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/18015)/[Video](https://www.youtube.com/watch?v=RI4nt5MDmwE&ab_channel=TrungNgh%C4%A9aL%C3%AA)
|   2021   | TIFS | Integrating Part-Object Relationship and Contrast for Camouflaged Object Detection  <br><sup><sub>*Yi Liu, Dingwen Zhang, Qiang Zhang, and Jungong Han*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9600863/)/[Code](https://github.com/liuyi1989/TSPORTNet)
|   2021   | TIE | D2C-Net: A Dual-branch, Dual-guidance and Cross-refine Network for Camouflaged Object Detection <br><sup><sub>*Kang Wang, Hongbo Bi, Yi Zhang, Cong Zhang, Ziqi Liu, Shuang Zheng*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/9430677)/[Code](https://github.com/MS-KangWang/COD-D2Net)
|   2021   |  TCSVT   | Deep Texture-Aware Features for Camouflaged Object Detection <br><sup><sub>*Jingjing Ren, Xiaowei Hu, Lei Zhu, Xuemiao Xu, et al.*</sub></sup>  | [Paper](https://arxiv.org/pdf/2102.02996.pdf)/Code 
|  2021   |  TCSVT  | Rethinking Camouflaged Object Detection: Models and Datasets <br><sup><sub>*Hongbo Bi, Cong Zhang, Kang Wang, Jinghui Tong, Feng Zheng*</sub></sup>   | [Paper](https://ieeexplore.ieee.org/document/9598866)/Code
|   2021   |   Access | MirrorNet: Bio-Inspired Camouflaged Object Segmentation <br><sup><sub>*Jinnan Yan, Trung-Nghia Le, Khanh-Duy Nguyen, Minh-Triet Tran, Thanh-Toan Do, Tam V. Nguyen*</sub></sup>  | [Paper](https://arxiv.org/abs/2007.12881)/[Project](https://sites.google.com/view/ltnghia/research/camo)
|   2021   |  arXiv   | Exploring Depth Contribution for Camouflaged Object Detection <br> <sup><sub>*Mochu Xiang, Jing Zhang, Yunqiu Lv, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2106.13217v3)/Code
|   2021   |  arXiv   | Towards Accurate Camouflaged Object Detection with Mixture Convolution and Interactive Fusion <br> <sup><sub>*Bo Dong, Mingchen Zhuge, Yongxiong Wang, Hongbo Bi, Geng Chen*</sub></sup> | [Paper](https://arxiv.org/pdf/2101.05687.pdf)/[Code](https://github.com/BigHeartDB/MCIFNet)  

####  2.2.4. <a name='BeforeYEAR2020'></a>Before YEAR 2020 

| **Year** | **Publication** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2020   |   CVPR   | **Camouflaged Object Detection** (`SINet & COD10K dataset`)                            <br><sup><sub>*Deng-Ping Fan, Ge-Peng Ji, Guolei Sun, Ming-Ming Cheng, Jianbing Shen, Ling Shao*</sub></sup>                                         | [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fan_Camouflaged_Object_Detection_CVPR_2020_paper.pdf)/[Code](https://github.com/DengPingFan/SINet)           |
|   2019   |   CVIU   | Anabranch network for camouflaged object segmentation (`CAMO dataset`) <br><sup><sub>*Trung-Nghia Le, Tam V. Nguyen, Zhongliang Nie, Minh-Triet Tran, Akihiro Sugimoto*</sub></sup>  | [Paper](http://www.dgcv.nii.ac.jp/Publications/Papers/2019/cviu2019.pdf)/[Code](https://sites.google.com/view/ltnghia/research/camo)
|   2019   |   SPL    | Detection of People With Camouflage Pattern Via Dense Deconvolution Network (`CPD1K dataset`) <br><sup><sub>*Yunfei Zheng, Xiongwei Zhang, Feng Wang, Tieyong Cao, Meng Sun, Xiaobing Wang*</sub></sup>  | [Paper](https://ieeexplore.ieee.org/document/8336933)/Code
|   2018   |   TIP    | A Fusion Framework for Camouflaged Moving Foreground Detection in the Wavelet Domain <br><sup><sub>*Shuai Li, Dinei Florencio, Wanqing Li, Yaqin Zhao, Chris Cook*</sub></sup>                                              | [Paper](https://arxiv.org/abs/1804.05984)/Code                                                   |
|   2016   |   IJCV   | <span style="white-space:nowrap;">Partially Camouflaged Object Tracking using Modified Probabilistic Neural Network and Fuzzy Energy based Active Contour&emsp;&emsp;&emsp;</span> <br><sup><sub>*Ajoy Mondal, Susmita Ghosh, Ashish Ghosh*</sub></sup>  | [Paper](https://link.springer.com/article/10.1007/s11263-016-0959-5)/Code        



###  2.3. <a name='CamouflagedInstanceSegmentationCIS'></a>Camouflaged Instance Segmentation (CIS)


| **Year** | **Publication** | **Title**                                                    | **Links**                                                    |
| :------: | :------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|   2022   |  ECCV    | **OSFormer: One-Stage Camouflaged Instance Segmentation with Transformers** <br> <sup><sub>*Jialun Pei, Tianyang Cheng, Deng-Ping Fan, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2207.02255)/[Code](https://github.com/PJLallen/OSFormer)
|   2022   |  TIP  | Camouflaged Instance Segmentation In-The-Wild: Dataset, Method, and Benchmark Suite <br> <sup><sub>*Trung-Nghia Le, Yubo Cao, Tan-Cong Nguyen, et al.*</sub></sup> | [Paper](https://arxiv.org/abs/2103.17123)/[Project](https://sites.google.com/view/ltnghia/research/camo_plus_plus)


###  2.4. <a name='VideoCamouflagedObjectDetectionVCOD'></a>Video Camouflaged Object Detection (VCOD)

| **Year** | **Publication** | **Title**          | **Links**        |
| :------: | :------: | :----------------------------------------------------------- |  :----------------------------------------------------------- |
|   2022   |   CVPR   | **Implicit Motion Handling for Video Camouflaged Object Detection** (`MoCA-Mask dataset`) <br> <sup><sub>*Xuelian Cheng, Huan Xiong, Deng-Ping Fan, et al.*</sub></sup> | [Paper](https://dengpingfan.github.io/papers/[2022][CVPR]VCOD_MoCA-Mask.pdf)/[Code](https://github.com/XuelianCheng/SLT-Net)
| 2022 | TPAMI | EM-driven unsupervised learning for efficient motion segmentation <br> <sup><sub>*Etienne Meunier, Ana¨ıs Badoual, and Patrick Bouthemy.*</sub></sup> | [Paper](https://ieeexplore.ieee.org/document/9855882)/[Code](https://github.com/Etienne-Meunier-Inria/EM-Flow-Segmentation)
| 2022 | NeurIPS |Segmenting Moving Objects via an Object-Centric Layered Representation <br> <sup><sub>*Junyu Xie, Weidi Xie, Andrew Zisserman.*</sub></sup> | [Paper](https://openreview.net/pdf?id=tUH1Or4xblM)/Code
| 2022 | arXiv | The Right Spin: Learning Object Motion from Rotation-Compensated Flow Fields <br> <sup><sub>*Pia Bideau, Erik Learned-Miller, Cordelia Schmid, et al.*</sub></sup> | [Paper](https://arxiv.org/pdf/2203.00115.pdf)/Code
| 2021 | ICCV | Self-Supervised Video Object Segmentation by Motion Grouping <br> <sup><sub>*Charig Yang, Hala Lamdouar, Erika Lu, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Self-Supervised_Video_Object_Segmentation_by_Motion_Grouping_ICCV_2021_paper.pdf)/[Code](https://charigyang.github.io/motiongroup/)
| 2021 | BMVC | Segmenting Invisible Moving Objects <br> <sup><sub>*Hala Lamdouar, Weidi Xie, and Andrew Zisserman.*</sub></sup> | [Paper](https://www.bmvc2021-virtualconference.com/assets/papers/0056.pdf)/[Code](https://www.robots.ox.ac.uk/~vgg/research/simo/)
| 2020 | ACCV |Betrayed By Motion: Camouflaged Object Discovery via Motion Segmentation  (`MoCA dataset`)<br> <sup><sub>*Hala Lamdouar, Charig Yang, Weidi Xie,et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content/ACCV2020/papers/Lamdouar_Betrayed_by_Motion_Camouflaged_Object_Discovery_via_Motion_Segmentation_ACCV_2020_paper.pdf)/[Code](https://github.com/hlamdouar/MoCA/)	
| 2019 | CVPR |Object discovery in videos as foreground motion clustering <br> <sup><sub>*Christopher Xie, Yu Xiang, Zaid Harchaoui, et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Xie_Object_Discovery_in_Videos_as_Foreground_Motion_Clustering_CVPR_2019_paper.pdf)/Code
| 2018 | CVPR |The best of both worlds: Combining cnns and geometric constraints for hierarchical motion segmentation <br> <sup><sub>*Pia Bideau, Aruni RoyChowdhury, Rakesh R. Menon,et al.*</sub></sup> | [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Bideau_The_Best_of_CVPR_2018_paper.pdf)/[Code](https://github.com/pbideau/hierarchical-motion-segmentation)
| 2016 | ECCV | <span style="white-space:nowrap;">It’s Moving! A Probabilistic Model for Causal Motion Segmentation in Moving Camera Videos&emsp;&emsp;&emsp;</span> <br><sup><sub>*Bideau, Pia, and Erik Learned-Miller.*</sub></sup> | [Paper](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_26)/Code
