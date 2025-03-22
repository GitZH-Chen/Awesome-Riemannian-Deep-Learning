# Awesome Deep Learning over Riemannian Spaces

🚀 This is an ongoing repo, containing resources on Riemannian deep learning.

🌟 **Note:** This repo does not inlcude Riemannian optimization. For that, please refer to [Awesome-Riemannian-Optimization](https://github.com/andyjm3/Awesome-Riemannian-Optimization) by [Andi Han](https://scholar.google.com/citations?user=AKHQHs0AAAAJ&hl=en).

<details open>
  <summary><h2><b> Contents </b></h2></summary>

  * [1. Books](#1-books)
    * [Topology](#topology)
  	* [Differential Geometry](#differential-geometry)
  	* [Riemannian Geometry](#riemannian-geometry)
    * [Lie Groups](#lie-groups)
    * [Riemannian Optimization](#riemannian-optimization)
  * [2. Papers](#2-papers)
    * [Popular Manifolds](#popular-manifolds)
    * [Geometries](#geometries)
      * [SPD Geometries](#spd-geometries)
      * [Grassmannian](#grassmannian)
      * [Lie Groups](#lie-groups)
    * [SPD Neural Networks](#spd-neural-networks)
    * [Grassmannian Neural Networks](#grassmannian-neural-networks)
    * [Lie Group Neural Networks](#lie-group-neural-networks)
    * [Constant Curvature Neural Networks](#constant-curvature-neural-networks)
    * [Riemannian Graph Neural Networks](#riemannian-graph-neural-networks)
    * [Neuroscience Applications](#neuroscience-applications)
    * [Riemannian Networks on General Geometries](#riemannian-networks-on-general-geometries)
    * [Riemannian Generative Networks](#riemannian-generative-networks)
    * [Applications](#applications)
      * [Neuroscience Applications](#neuroscience-applications)
      * [High-order Pooling](#high-order-pooling)
      * [Others](#others)

      </details>

# 1 Books
##  Topology
- [Basic Topology](https://link.springer.com/book/10.1007/978-1-4757-1793-8) Springer,1983.
- [Topology](http://www.alefenu.com/libri/topologymunkres.pdf) Pearson, 2000.

##  Differential Geometry
- [An Introduction to Manifolds](https://link.springer.com/book/10.1007/978-1-4419-7400-6) Springer, 2011. 
- [Introduction to Smooth Manifolds](https://link.springer.com/book/10.1007/978-1-4419-9982-5) Springer, 2012.


##  Riemannian Geometry
- [Riemannian Geometry](https://link.springer.com/book/9780817634902) Birkhäuser, 1992.
- [Introduction to Riemannian Manifolds](https://link.springer.com/book/10.1007/978-3-319-91755-9) Springer, 2018.
- [Riemannian Geometry](https://link.springer.com/book/10.1007/978-3-319-26654-1) Springer, 2006.

##  Lie Groups
- [Naive Lie Theory](https://link.springer.com/book/10.1007/978-0-387-78214-0) Springer, 2008.
- [Lie Groups, Lie Algebras, and Representations](https://link.springer.com/book/10.1007/978-3-319-13467-3) Springer, 2015.
- [A mathematical introduction to robotic manipulation](https://doi.org/10.1201/9781315136370)
- [Rotation Averaging](https://doi.org/10.1007/s11263-012-0601-0) IJCV 2013

##  Hyperbolic Geometry
- [Hyperbolic Geometry](https://www.math.ucdavis.edu/~kapovich/RFG/cannon.pdf) 
- [A Gyrovector Space Approach to Hyperbolic Geometry](https://link.springer.com/book/10.1007/978-3-031-02396-5) Springer, 2009.

##  Riemannian Optimization
1. [Optimization Algorithms on Matrix Manifolds](https://press.princeton.edu/absil?srsltid=AfmBOorlfmgaTCzFeGcEDw9mxNrVvWMaKhY578kDlMOKlYY9D-G9ar3n) Cambridge University Press, 2023
2. [An introduction to Optimization on smooth manifolds](https://www.nicolasboumal.net/book/) Princeton University Press, 2008.

# 2 Papers

## Popular Manifolds
> An overview can be found in https://www.manopt.org/manifolds.html

## Geometries

### Riemannian Metric Learning
- [Learning Riemannian Metrics for Interpolating Animations](https://openreview.net/forum?id=u1erMPtujY) Openreview 2024
- [Riemann<sup>2</sup>: Learning Riemannian Submanifolds from Riemannian Data](https://arxiv.org/pdf/2503.05540) AISTATS 2025
- [Riemannian Metric Learning: Closer to You than You Imagine](https://arxiv.org/pdf/2503.05321#page=23.23) Arxiv 2025

### SPD Geometries
- [Fast and Simple Computations on Tensors with Log-Euclidean Metrics](https://inria.hal.science/inria-00070423/document) Reaserch Report 2005
- [A Riemannian framework for tensor computing](https://link.springer.com/article/10.1007/s11263-005-3222-z) IJCV 2006
- [Power Euclidean metrics for covariance matrices with application to diffusion tensor imaging](https://arxiv.org/abs/1009.3045) Arxiv 2010
- [Riemannian geometry of symmetric positive definite matrices via Cholesky decomposition](https://doi.org/10.1137/18M1221084) SIMAX 2019
- [On the Bures–Wasserstein distance between positive definite matrices](https://doi.org/10.1016/j.exmath.2018.01.002) Expositiones Mathematicae 2019
- [The geometry of mixed-Euclidean metrics on symmetric positive definite matrices](https://doi.org/10.1016/j.difgeo.2022.101867) Differential Geometry and its Applications 2022
- [O (n)-invariant Riemannian metrics on SPD matrices](https://doi.org/10.1016/j.laa.2022.12.009) Linear Algebra and its Applications 2023
- [Learning with symmetric positive definite matrices via generalized Bures-Wasserstein geometry](https://doi.org/10.1007/978-3-031-38271-0_40) GSI 2023
- [Adaptive Log-Euclidean Metrics for SPD Matrix Learning](https://arxiv.org/abs/2303.15477) TIP 2024
- [Product Geometries on Cholesky Manifolds with Applications to SPD Manifolds](https://arxiv.org/abs/2407.02607) Arxiv 2024
- [Wrapped Gaussian on the manifold of Symmetric Positive Definite Matrices](https://arxiv.org/abs/2502.01512) Arxiv 2025
- [A Riemannian covariance for manifold-valued data](https://arxiv.org/abs/2410.06164) Arxiv 2025

### Grassmannian
- [The Geometry of Algorithms with Orthogonality Constraints](https://doi.org/10.1137/S0895479895290954) SIMAX 1998
- [A Grassmann Manifold Handbook: Basic Geometry and Computational Aspects](https://arxiv.org/abs/2011.13699) Advances in Computational Mathematics 2024

### Lie Groups
- [Left-Invariant Riemannian Geodesics on Spatial Transformation Groups](https://epubs.siam.org/doi/10.1137/130928352) SIIMS 2014
- [Optimal Transport on the Lie Group of Roto-translations](https://arxiv.org/abs/2402.15322) SIIMS 2024


## SPD Neural Networks
### Network Construction
- [A Riemannian Network for SPD Matrix Learning](https://arxiv.org/abs/1608.04233) AAAI 2017
- [Riemannian batch normalization for SPD neural networks](https://arxiv.org/abs/1909.02414) NeurIPS 2019
- [GeomNet: A Neural Network Based on Riemannian Geometries of SPD Matrix Space and Cholesky Space for 3D Skeleton-Based Interaction Recognition](https://arxiv.org/abs/2111.13089) ICCV 2021
- [Neural Architecture Search of SPD Manifold Networks](https://arxiv.org/abs/2010.14535) IJCAI 2021
- [Vector-valued Distance and Gyrocalculus on the Space of Symmetric Positive Definite Matrices](https://arxiv.org/abs/2110.13475) NeurIPS 2021
- [Riemannian Local Mechanism for SPD Neural Networks](https://ojs.aaai.org/index.php/AAAI/article/view/25867) AAAI 2023
- [SPD Manifold Deep Metric Learning for Image Set Classification](https://ieeexplore.ieee.org/document/10467142) TNNLS 2024
- [Riemannian Multinomial Logistics Regression for SPD Neural Networks](https://arxiv.org/abs/2305.11288) CVPR 2024
- [Exploring the Enigma of Neural Dynamics Through A Scattering-Transform Mixer Landscape for Riemannian Manifold](https://arxiv.org/abs/2405.16357) ICML 2024
- [Schur's Positive-Definite Network: Deep Learning in the SPD cone with structure](https://openreview.net/forum?id=v1B4aet9ct) ICLR 2025



## Grassmannian Neural Networks
- [Building Deep Networks on Grassmann Manifolds](https://arxiv.org/abs/1611.05742) AAAI 2018
- [A Grassmannian Manifold Self-Attention Network for Signal Classification](https://www.ijcai.org/proceedings/2024/564) IJCAI 2024

## Lie Group Neural Networks
- [Human Action Recognition by Representing 3D Skeletons as Points in a Lie Group](https://ieeexplore.ieee.org/document/6909476) CVPR 2014
- [Rolling rotations for recognizing human actions from 3d skeletal data](https://ieeexplore.ieee.org/document/7780853) CVPR 2016
- [Deep Learning on Lie Groups for Skeleton-based Action Recognition](https://arxiv.org/abs/1612.05877) CVPR 2017

## Constant Curvature Neural Networks
- [Hyperbolic entailment cones for learning hierarchical embeddings](https://proceedings.mlr.press/v80/ganea18a.html) ICML 2018
- [Learning Continuous Hierarchies in the Lorentz Model of Hyperbolic Geometry](https://arxiv.org/abs/1806.03417) ICML 2018
- [Hyperbolic Neural Networks](https://arxiv.org/abs/1805.09112) NeurIPS 2018
- [Poincaré GloVe: Hyperbolic Word Embeddings](https://openreview.net/forum?id=Ske5r3AqK7)  ICLR 2019
- [Hyperbolic Attention Networks](https://openreview.net/forum?id=rJxHsjRqFQ) ICLR 2019
- [Continuous Hierarchical Representations with Poincaré Variational Auto-Encoders](https://arxiv.org/abs/1901.06033) NeurIPS 2019
- [Mixed-curvature Variational Autoencoders](https://openreview.net/forum?id=S1g6xeSKDS) ICLR 2020
- [Hyperbolic Neural Networks++](https://arxiv.org/abs/2006.08210) ICLR 2021
- [Differentiating through the Fréchet Mean](https://arxiv.org/abs/2003.00335) ICML 2020
- [Curvature Generation in Hyperbolic Spaces for Few-Shot Learning](https://ieeexplore.ieee.org/document/9711172) ICCV 2021
- [Fully Hyperbolic Neural Networks](https://arxiv.org/abs/2105.14686) ACL 2022
- [Nested hyperbolic spaces for dimensionality reduction and hyperbolic nn design](https://arxiv.org/abs/2112.03402) CVPR 2022
- [Hyperbolic Feature Augmentation via Distribution Estimation and Infinite Sampling on Manifolds](https://openreview.net/forum?id=yoLGaLPEPo) NeurIPS 2022
- [Poincaré ResNet](https://arxiv.org/abs/2303.14027) ICCV 2023
- [Fully Hyperbolic Convolutional Neural Networks for Computer Vision](https://openreview.net/forum?id=ekz1hN5QNh) ICLR 2024
- [Lorentzian Residual Neural Networks](https://arxiv.org/abs/2412.14695) KDD 2025
- [Compositional Entailment Learning for Hyperbolic Vision-Language Models](https://openreview.net/forum?id=3i13Gev2hV) ICLR 2025

## Riemannian Graph Neural Networks
- [Computationally Tractable Riemannian Manifolds for Graph Embeddings](https://doi.org/10.1609/aaai.v35i8.16877) AAAI 2021
- [Graph Neural Networks on SPD Manifolds for Motor Imagery Classification: A Perspective from the Time-Frequency Analysis](https://arxiv.org/abs/2211.02641) TNNLS 2023
- [Modeling Graphs Beyond Hyperbolic: Graph Neural Networks in Symmetric Positive Definite Matrices](https://arxiv.org/abs/2306.14064) ECML 2023

- [Hyperbolic Graph Convolutional Neural Networks](https://arxiv.org/abs/1910.12933) NeurIPS 2019
- [Hyperbolic Graph Neural Networks](https://arxiv.org/abs/1910.12892) NeurIPS 2019
- [Constant Curvature Graph Convolutional Networks](https://arxiv.org/abs/1911.05076) ICML 2020
- [A Hyperbolic-to-Hyperbolic Graph Convolutional Network](https://arxiv.org/pdf/2104.06942) CVPR 2021
- [LSEnet: Lorentz Structural Entropy Neural Network for Deep Graph Clustering](https://arxiv.org/abs/2405.11801) ICML 2024
- [Spiking Graph Neural Network on Riemannian Manifolds](https://arxiv.org/abs/2410.17941) NeurIPS 2024
- [A Mixed-Curvature Graph Diffusion Model](https://dl.acm.org/doi/abs/10.1145/3627673.3679708?casa_token=AeZEppU7riIAAAAA:cie2_B_3MR3ut6RmJ1oHBxb85_6OP4g1HF3vXLLdzjqNLI8usy2i7N_eKeR0Rywy6x71P0uuwzw) CIKM 2024
- [Pioneer: Physics-informed Riemannian Graph ODE for Entropy-increasing Dynamics](https://arxiv.org/abs/2502.03251) AAAI 2025
- [RiemannGFM: Learning a Graph Foundation Model from Riemannian Geometry](https://arxiv.org/abs/2502.03251) WWW 2025

## Riemannian Networks on General Geometries
- [Dilated Convolutional Neural Networks for Sequential Manifold-valued Data](https://arxiv.org/abs/1910.02206) ICCV 2019
- [ManifoldNet: A Deep Neural Network for Manifold-Valued Data With Applications](https://ieeexplore.ieee.org/document/9122448) TPAMI 2020
- [ManifoldNorm: Extending normalizations on Riemannian Manifolds](https://arxiv.org/abs/2003.13869) Arxiv 2020

- [A Gyrovector Space Approach for Symmetric Positive Semi-definite Matrix Learning](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870052.pdf) ECCV 2022
- [The Gyro-Structure of Some Matrix Manifolds](https://openreview.net/forum?id=eyE9Fb2AvOT) NeurIPS 2022
- [Building Neural Networks on Matrix Manifolds: A Gyrovector Space Approach](https://arxiv.org/abs/2305.04560) ICML 2023
- [Riemannian Residual Neural Networks](https://arxiv.org/abs/2310.10013) NeurIPS 2023
- [Matrix Manifold Neural Networks++](https://openreview.net/forum?id=30aSE3FB3L) ICLR 2024
- [A Lie Group Approach to Riemannian Batch Normalization](https://openreview.net/forum?id=okYdj8Ysru) ICLR 2024
- [RMLR: Extending Multinomial Logistic Regression into General Geometries](https://arxiv.org/abs/2409.19433) NeurIPS 2024
- [Gyrogroup Batch Normalization](https://openreview.net/forum?id=d1NWq4PjJW) ICLR 2025
- [Neural Networks on Symmetric Spaces of Noncompact Type](https://openreview.net/forum?id=bwOndfohRK&noteId=XBiz6RG96t) ICLR 2025
- [GyroAtt: A Gyro Attention Framework for Matrix Manifolds](https://openreview.net/forum?id=YcaFqY8LWD) Openreview 2025

## Riemannian Generative Networks
- [Riemannian score-based generative modelling](https://arxiv.org/abs/2202.02763) NeurIPS 2022
- [Riemannian Diffusion Models](https://openreview.net/forum?id=ecevn9kPm4) NeurIPS 2022
- [SE (3) diffusion model with application to protein backbone generation](https://arxiv.org/abs/2302.02277) ICML 2023
- [Exploring Data Geometry for Continual Learning](https://arxiv.org/abs/2304.03931) CVPR 2023
- [Scaling Riemannian Diffusion Models](https://arxiv.org/abs/2310.20030) NeurIPS 2023
- [Flow Matching on General Geometries](https://arxiv.org/abs/2302.03660) ICLR 2024
- [Hyperbolic Geometric Latent Diffusion Model for Graph Generation](https://arxiv.org/abs/2405.03188) ICML 2024
- [Generative Modeling on Lie Groups via Euclidean Generalized Score Matching](https://arxiv.org/abs/2502.02513) Arxiv 2025

## Applications

### Neuroscience Applications
- [MAtt: A Manifold Attention Network for EEG Decoding](https://openreview.net/forum?id=YG4Dg7xtETg) NeurIPS 2022
- [Deep Optimal Transport for Domain Adaptation on SPD Manifolds](https://arxiv.org/abs/2201.05745) Arxiv 2024
- [SPD domain-specific batch normalization to crack interpretable unsupervised domain adaptation in EEG](https://arxiv.org/abs/2206.01323) NeurIPS 2024
- [Deep Geodesic Canonical Correlation Analysis for Covariance-Based Neuroimaging Data](https://openreview.net/forum?id=PnR1MNen7u) ICLR 2024
- [Exploring the Enigma of Neural Dynamics Through A Scattering-Transform Mixer Landscape for Riemannian Manifold](https://arxiv.org/abs/2405.16357) ICML 2024
- [GeoMind: A Geometric Neural Network of State Space Model for Understanding Brain Dynamics on Riemannian Manifold](https://openreview.net/forum?id=YZdc7mTq7I) Openreview 2025
- [SPDIM: Source-Free Unsupervised Conditional and Label Shift Adaptation in EEG](https://openreview.net/forum?id=CoQw1dXtGb) ICLR 2025
- [Hyperbolic Genome Embeddings](https://openreview.net/forum?id=NkGDNM8LB0) ICLR 2025

### High-order Pooling
- [Kernel Pooling for Convolutional Neural Networks](https://openaccess.thecvf.com/content_cvpr_2017/html/Cui_Kernel_Pooling_for_CVPR_2017_paper.html) CVPR 2017
- [Towards Faster Training of Global Covariance Pooling Networks by Iterative Matrix Square Root Normalization](https://arxiv.org/abs/1712.01034) CVPR 2018
- [DeepKSPD: Learning Kernel-matrix-based SPD  Representation for Fine-grained Image Recognition](https://doi.org/10.1007/978-3-030-01216-8_38) ECCV 2018
- [Deep CNNs Meet Global Covariance Pooling: Better Representation and Generalization](https://arxiv.org/abs/1904.06836) TPAMI 2020
- [Orthogonal SVD Covariance Conditioning and Latent Disentanglement](https://ieeexplore.ieee.org/abstract/document/9983471) TPAMI 2022
- [Fast Differentiable Matrix Square Root and Inverse Square Root](https://ieeexplore.ieee.org/abstract/document/9926140) TPAMI 2022
- [On the Eigenvalues of Global Covariance Pooling for Fine-grained Visual Recognition](https://ieeexplore.ieee.org/abstract/document/9785385) TPAMI 2022
- [Learning partial correlation based deep visual representation for image classification](https://arxiv.org/abs/2304.11597) CVPR 2023
- [Understanding Matrix Function Normalizations in Covariance Pooling through the Lens of Riemannian Geometry](https://openreview.net/forum?id=q1t0Lmvhty) ICLR 2025

### Others
- [HYperbolic Self-Paced Learning for Self-Supervised Skeleton-based Action Representations](https://arxiv.org/abs/2303.06242) ICLR 2023
- [Geometry-Aware Deep Learning for 3D Skeleton-Based Motion Prediction](https://openaccess.thecvf.com//content/WACV2025/papers/Zaier_Geometry-Aware_Deep_Learning_for_3D_Skeleton-Based_Motion_Prediction_WACV_2025_paper.pdf) WACV 2025
