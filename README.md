## 2D-3D-Matching  

### Case 1 : Papers for 2D-3D correspondences.... 
| Year | Paper | link | Code | Extra.  |
| --- | --- | --- | --- |  --- |  
|[ECCV2020]| Learning 2D–3D Correspondences To Solve The Blind Perspective-n-Point Problem   |  [PDF1](https://arxiv.org/pdf/2003.06752.pdf) [PDF2](https://arxiv.org/pdf/2007.14628.pdf) |  [Github](https://github.com/Liumouliu/Deep_blind_PnP)  | [Youtube](https://www.youtube.com/watch?v=f5jZ5CojNe0) **Note** Output is the prioritized matches & estimated camera pose |  
| [Arxiv, April2019] |  2D3D-MatchNet: Learning to Match Keypoints Across 2D Image and 3D Point Cloud  | [PDF](https://arxiv.org/pdf/1904.09742.pdf) | [github](  https://github.com/mengdanfeng/2D3D-MatchNet) | Output is the prioritized matches  |
| [CVPR2018] | Learning Less is More – 6D Camera Localization via 3D Surface Regression | [PDF](https://openaccess.thecvf.com/content_cvpr_2018/papers/Brachmann_Learning_Less_Is_CVPR_2018_paper.pdf) | [github](https://github.com/vislearn/LessMore)  | Output is the estimated camera pose  | 
| [ICCV2019]* | Expert Sample Consensus Applied to Camera Re-Localization (ESAC) | [PDF](https://arxiv.org/pdf/1908.02484.pdf) | [github](https://github.com/vislearn/esac)  | Output is the estimated camera pose. It extended LessisMore(CVPR2018) for large scale dataset.  | 
| [CVPR2020]* | KFNet: Learning Temporal Camera Relocalization using Kalman Filtering | [PDF](https://arxiv.org/pdf/1908.02484.pdf) | [github](https://github.com/zlthinker/KFNet)  | Output is the estimated camera pose. SCoordNet is the 1-short retrieval version of KFNet.    | 

**Note:** SCoordNet outperforms the state-of-the-art structure-based methods DSAC++ [6] and ESAC [7],  yet with fewer parameters (24M vs. 210M vs. 28M, respectively).

### Case 2 :  Papers for Localization where 2D images is given to match 3D SfM.... 
| Year | Paper | link | Code | Extra.  |
| --- | --- | --- | --- |  --- | 
|ICCV 2019| Cascaded Parallel Filtering for Memory-Efficient Image-Based Localization | [PDF](https://openaccess.thecvf.com/content_ICCV_2019/html/Cheng_Cascaded_Parallel_Filtering_for_Memory-Efficient_Image-Based_Localization_ICCV_2019_paper.html) | [github](https://github.com/wentaocheng-cv/cpf_localization) |  **Note** SIFT is used in SfM database | 
|CVPR 2019| HF-Net: Robust Hierarchical Localization at Large Scale | [PDF](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sarlin_From_Coarse_to_Fine_Robust_Hierarchical_Localization_at_Large_Scale_CVPR_2019_paper.pdf) | [github](https://github.com/ethz-asl/hfnet) |  **Note** SIFT/SuperPoints is used in SfM database |        

### Case 3 : 3D point features.... 
| Year | Paper | link | Code | Extra.  |
| --- | --- | --- | --- |  --- |  
| ECCV 2020 |  DH3D: Deep Hierarchical 3D Descriptors for Robust Large-Scale 6DoF Relocalization | [PDF](https://arxiv.org/pdf/2007.09217.pdf)  |  [github](https://github.com/JuanDuGit/DH3D)  |  https://vision.in.tum.de/research/vslam/dh3d |
