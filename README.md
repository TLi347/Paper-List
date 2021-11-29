# Paper List
## Point Cloud Generation
1. Points2Surf: Learning Implicit Surfaces from Point Clouds (ECCV20)
 [[Paper](https://arxiv.org/pdf/2007.10453.pdf)][[github](https://github.com/ErlerPhilipp/points2surf)] (_Desc: Global & Local; QSTN_)
2. Score-Based Point Cloud Denoising (ICCV21)
 [[paper](https://arxiv.org/pdf/2107.10981.pdf)][[github](https://github.com/luost26/score-denoise)]  
3. Learning Gradient Fields for Shape Generation
 [[paper](https://arxiv.org/pdf/2008.06520.pdf)]
4. PointFlow : 3D Point Cloud Generation with Continuous Normalizing Flows (ICCV19)
 [[paper](https://github.com/stevenygd/PointFlow)]  (_Desc: ODE_)
5. Variational Relational Point Completion Network (CVPR21)
 [[paper](https://paul007pl.github.io/projects/VRCNet)][[github](https://paul007pl.github.io/projects/VRCNet)] (_Desc: dual-path architecture; Relational Enhancement; MVP dataset_)
6. ChartPointFlow for Topology-Aware 3D Point Cloud Generation (MM21) [[paper](https://dl.acm.org/doi/pdf/10.1145/3474085.3475589)] (_Desc: part-edit_)
7. Orienting Point Clouds with Dipole Propagation (SIGGRAPH21) [[paper](https://cims.nyu.edu/gcl/papers/2021-Dipole.pdf)] (_Desc: normal opt_)
8. DSG-Net: Learning Disentangled Structure and Geometry for 3D Shape Generation [[paper](https://arxiv.org/pdf/2008.05440.pdf)] [[]()]
9. Sign-Agnostic Implicit Learning of Surface Self-Similarities for Shape Modeling and Reconstruction from Raw Point Clouds (CVPR21) [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhao_Sign-Agnostic_Implicit_Learning_of_Surface_Self-Similarities_for_Shape_Modeling_and_CVPR_2021_paper.pdf)]
10. Deep Hough Voting for 3D Object Detection in Point Clouds (ICCV19) 
[[paper](https://arxiv.org/pdf/1904.09664.pdf)] [[github](https://github.com/facebookresearch/votenet)] (_Desc: 3D detection; PointNet++;_)
11. 3D Shape Generation and Completion through Point-Voxel Diffusion (NeurIPS21)
 [[paper](https://arxiv.org/pdf/2104.03670.pdf)]
12. LOGAN: Unpaired Shape Transform in Latent Overcomplete Space (SIGAsia20)
[[paper](https://arxiv.org/pdf/1903.10170.pdf)][[github](https://github.com/kangxue/LOGAN)] (_Desc:_)
13. 3D Point Capsule Networks (CVPR20)
[[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhao_3D_Point_Capsule_Networks_CVPR_2019_paper.pdf)] [[github](https://github.com/yongheng1991/3D-point-capsule-networks)]
15. Conditional Point Diffusion-Refinement [[paper](https://openreview.net/pdf?id=wqD6TfbYkrn)]
16. 

## Dynamic Point Cloud
1. FlowNet3D: Learning Scene Flow in 3D Point Clouds  [[paper]()]
2. MeteorNet: Deep Learning on Dynamic 3D Point Cloud Sequences(ICCV19)  [[paper](https://arxiv.org/abs/1910.09165)]
3. Occupancy Flow: 4D Reconstruction by Learning Particle Dynamics (ICCV19) [[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Niemeyer_Occupancy_Flow_4D_Reconstruction_by_Learning_Particle_Dynamics_ICCV_2019_paper.pdf)]
4. CaSPR: Learning Canonical Spatiotemporal Point Cloud Representations (NeurIPS20)
[[paper](https://arxiv.org/pdf/2008.02792.pdf%5C%22)][[github](https://github.com/davrempe/caspr)] (_Desc: spacetime continuity; robustness; category-level generalization;  spatiotemporal(ST) changes;_)
<!-- First, we explicitly encode time by mapping an input point cloud sequence to a spatiotemporally-canonicalized object space. We then leverage this canonicalization to learn a spatiotemporal latent representation using neural ordinary differential equations and a generative model of dynamically evolving shapes using continuous normalizing flows. -->
<!-- Yet, important limitations remain in terms of the lack of temporal continuity, robustness, and category-level generalization -->
5. dada
6.  


## General Method
1. Flow++: Improving Flow-Based Generative Models with Variational Dequantization and Architecture Design 
 [[Paper](https://github.com/aravindsrinivas/flowpp)][[github](https://github.com/aravindsrinivas/flowpp)] (_Desc: Density?_)
2. Denoising Diffusion Probabilistic Models (DDPM) [[paper](https://arxiv.org/pdf/2006.11239.pdf)] [[github](https://github.com/hojonathanho/diffusion)]
3. Guided DDPM [[paper](https://arxiv.org/pdf/2102.09672.pdf)] [[github](https://github.com/openai/improved-diffusion)]
4. Neural Spatio-Temporal Point Processes (ICLR21) [[paper](https://arxiv.org/pdf/2011.04583.pdf)][[github]()] <!-- TBC -->
5. PatchVAE: Learning Local Latent Codes for Recognition (CVPR20) [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Gupta_PatchVAE_Learning_Local_Latent_Codes_for_Recognition_CVPR_2020_paper.pdf)]
6. 

## Mesh Related
1. Neural Parts: Learning Expressive 3D Shape Abstractions with Invertible Neural Networks (CVPR21) [[homepage](https://paschalidoud.github.io/neural_parts)][[paper](https://arxiv.org/pdf/2103.10429.pdf)]
2. Point2Mesh: A Self-Prior for Deformable Meshes (SIGGRAPH20) [[paper](https://arxiv.org/pdf/2005.11084.pdf)]
3. Shape As Points: A Differentiable Poisson Solver (NeurIPS21)  [[paper](https://github.com/autonomousvision/shape_as_points)] [[github](https://github.com/autonomousvision/shape_as_points)]
4. DeepMetaHandles: Learning Deformation Meta-Handles of 3D Meshes with Biharmonic Coordinates [[paper](https://arxiv.org/pdf/2102.09105.pdf)] (_Desc:_)
5. Deep Geometric Prior for Surface Reconstruction (CVPR19) [[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Williams_Deep_Geometric_Prior_for_Surface_Reconstruction_CVPR_2019_paper.pdf)]
6. Meshlet Priors for 3D Mesh Reconstruction [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Badki_Meshlet_Priors_for_3D_Mesh_Reconstruction_CVPR_2020_paper.pdf)] [no code]


## Algorithm & Datasets & Tools
1. MCMC Sample
 [[link1](https://zhuanlan.zhihu.com/p/351616020)] [[link2](https://github.com/wiseodd/MCMC)] [[link3](https://zhuanlan.zhihu.com/p/37121528)]
2. MANO Datasets (Hand)
 [[link1](https://github.com/otaheri/MANO)] [[link2](https://mano.is.tue.mpg.de/)]
3. COSEG Shape Datasets
 [[link](http://irc.cs.sdu.edu.cn/~yunhai/public_html/ssl/ssd.htm)]
4. PC render
 [[link](https://github.com/zekunhao1995/PointFlowRenderer)] [[mitsuba2](https://github.com/mitsuba-renderer/mitsuba2)]
