# Awesome Riemannian Deep Learning
🌟 This is an ongoing repo, containing resources on Riemannian deep learning.


<details open>
  <summary><h2><b> Contents </b></h2></summary>

  * [1. Books](#1-books)
    * [Topology](#topology)
  	* [Differential Geometry](#differential-geometry)
  	* [Riemannian Geometry](#riemannian-geometry)
    * [Lie Group](#lie-groups)
    * [Riemannian Optimization](#riemannian-optimization)
  * [2. Papers](#2-papers)
    * [Popular Manifolds](#popular-manifolds)
    * [SPD Neural Networks](#spd-neural-networks)
    * [Grassmannian Neural Networks](#grassmannian-neural-networks)
    * [Constant Curvature Neural Networks](#constant-curvature-neural-networks)
    * [Riemannian Networks on General Geometries](#riemannian-networks-on-general-geometries)
    * [Riemannian Generative Networks](#riemannian-networks-on-general-geometries)
    * [Applications in Euclidean Deep Learning](#)
      * [High-order Pooling](#)

      </details>

# 1 Books
##  Topology
1. [Basic Topology](https://link.springer.com/book/10.1007/978-1-4757-1793-8) Springer,1983.
2. [Topology](http://www.alefenu.com/libri/topologymunkres.pdf) Pearson, 2000.

##  Differential Geometry
1. [An Introduction to Manifolds](https://link.springer.com/book/10.1007/978-1-4419-7400-6) Springer, 2011.
2. [Introduction to Smooth Manifolds](https://link.springer.com/book/10.1007/978-1-4419-9982-5) Springer, 2012.


##  Riemannian Geometry
1. [Riemannian Geometry](https://link.springer.com/book/9780817634902) Birkhäuser, 1992.
2. [Introduction to Riemannian Manifolds](https://link.springer.com/book/10.1007/978-3-319-91755-9) Springer, 2018.
2. [Riemannian Geometry](https://link.springer.com/book/10.1007/978-3-319-26654-1) Springer, 2006.

##  Lie Groups
1. [Lie Groups, Lie Algebras, and Representations](https://link.springer.com/book/10.1007/978-3-319-13467-3) Springer, 2015.
2. [Naive Lie Theory](https://link.springer.com/book/10.1007/978-0-387-78214-0) Springer, 2008.

##  Hyperbolic Geometry
1. [Hyperbolic Geometry](https://www.math.ucdavis.edu/~kapovich/RFG/cannon.pdf)
2. [A Gyrovector Space Approach to Hyperbolic Geometry](https://link.springer.com/book/10.1007/978-3-031-02396-5) Springer, 2009.

##  Riemannian Optimization
1. [Optimization Algorithms on Matrix Manifolds](https://press.princeton.edu/absil?srsltid=AfmBOorlfmgaTCzFeGcEDw9mxNrVvWMaKhY578kDlMOKlYY9D-G9ar3n) Cambridge University Press, 2023
2. [An introduction to Optimization on smooth manifolds](https://www.nicolasboumal.net/book/) Princeton University Press, 2008.

# 2 Papers

## Popular Manifolds
> An overview can be found in https://www.manopt.org/manifolds.html
## Geometries

### SPD Geometries
- [Fast and Simple Computations on Tensors with Log-Euclidean Metrics](https://inria.hal.science/inria-00070423/document) Reaserch Report 2005
- [A Riemannian framework for tensor computing](https://link.springer.com/article/10.1007/s11263-005-3222-z) IJCV 2006
- [Power Euclidean metrics for covariance matrices with application to diffusion tensor imaging](https://arxiv.org/abs/1009.3045) Arxiv 2010
- [Riemannian geometry of symmetric positive definite matrices via Cholesky decomposition](https://doi.org/10.1137/18M1221084) SIMAX 2019
- [On the Bures–Wasserstein distance between positive definite matrices](https://doi.org/10.1016/j.exmath.2018.01.002) Expositiones Mathematicae 2019
- [The geometry of mixed-Euclidean metrics on symmetric positive definite matrices](https://doi.org/10.1016/j.difgeo.2022.101867) Differential Geometry and its Applications 2022
- [O (n)-invariant Riemannian metrics on SPD matrices](https://doi.org/10.1016/j.laa.2022.12.009) Linear Algebra and its Applications 2023
- [Learning with symmetric positive definite matrices via generalized Bures-Wasserstein geometry](https://doi.org/10.1007/978-3-031-38271-0_40) GSI 2023

### Grassmannian
- [The Geometry of Algorithms with Orthogonality Constraints](https://doi.org/10.1137/S0895479895290954) SIMAX 1998
- [A Grassmann Manifold Handbook: Basic Geometry and Computational Aspects](https://arxiv.org/abs/2011.13699) Advances in Computational Mathematics 2024

## SPD Neural Networks
### Network Construction
- [A Riemannian Network for SPD Matrix Learning](https://arxiv.org/abs/1608.04233) AAAI 2017
- [Riemannian batch normalization for SPD neural networks](https://arxiv.org/abs/1909.02414) NeurIPS 2019
- [GeomNet: A Neural Network Based on Riemannian Geometries of SPD Matrix Space and Cholesky Space for 3D Skeleton-Based Interaction Recognition](https://arxiv.org/abs/2111.13089) ICCV 2021
- [Neural Architecture Search of SPD Manifold Networks](https://arxiv.org/abs/2010.14535) IJCAI 2021
- [Vector-valued Distance and Gyrocalculus on the Space of Symmetric Positive Definite Matrices](https://arxiv.org/abs/2110.13475) NeurIPS 2021
- [Modeling Graphs Beyond Hyperbolic: Graph Neural Networks in Symmetric Positive Definite Matrices](https://arxiv.org/abs/2306.14064) ECML 2023
- [Riemannian Local Mechanism for SPD Neural Networks](https://ojs.aaai.org/index.php/AAAI/article/view/25867) AAAI 2023
- [SPD Manifold Deep Metric Learning for Image Set Classification](https://ieeexplore.ieee.org/document/10467142) TNNLS 2024
- [Riemannian Multinomial Logistics Regression for SPD Neural Networks](https://arxiv.org/abs/2305.11288) CVPR 2024
- [Exploring the Enigma of Neural Dynamics Through A Scattering-Transform Mixer Landscape for Riemannian Manifold](https://arxiv.org/abs/2405.16357) ICML 2024
- [Schur's Positive-Definite Network: Deep Learning in the SPD cone with structure](https://openreview.net/forum?id=v1B4aet9ct) ICLR 2025

### EEG Applications
- [MAtt: A Manifold Attention Network for EEG Decoding](https://openreview.net/forum?id=YG4Dg7xtETg) NeurIPS 2022
- [Graph Neural Networks on SPD Manifolds for Motor Imagery Classification: A Perspective from the Time-Frequency Analysis](https://arxiv.org/abs/2211.02641) TNNLS 2023
- [Deep Optimal Transport for Domain Adaptation on SPD Manifolds](https://arxiv.org/abs/2201.05745) Arxiv 2024
- [SPD domain-specific batch normalization to crack interpretable unsupervised domain adaptation in EEG](https://arxiv.org/abs/2206.01323) NeurIPS 2024
- [Deep Geodesic Canonical Correlation Analysis for Covariance-Based Neuroimaging Data](https://openreview.net/forum?id=PnR1MNen7u) ICLR 2024

## Grassmannian Neural Networks
- [Building Deep Networks on Grassmann Manifolds](https://arxiv.org/abs/1611.05742) AAAI 2018
- [A Grassmannian Manifold Self-Attention Network for Signal Classification](https://www.ijcai.org/proceedings/2024/564) IJCAI 2024

## Constant Curvature Neural Networks

## Riemannian Networks on General Geometries
- [Dilated Convolutional Neural Networks for Sequential Manifold-valued Data](https://arxiv.org/abs/1910.02206) ICCV 2019
- [ManifoldNet: A Deep Neural Network for Manifold-Valued Data With Applications](https://ieeexplore.ieee.org/document/9122448) TPAMI 2020
- [ManifoldNorm: Extending normalizations on Riemannian Manifolds](https://arxiv.org/abs/2003.13869) Arxiv 2020
- [Computationally Tractable Riemannian Manifolds for Graph Embeddings](https://doi.org/10.1609/aaai.v35i8.16877) AAAI 2021
- [A Gyrovector Space Approach for Symmetric Positive Semi-definite Matrix Learning](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136870052.pdf) ECCV 2022
- [The Gyro-Structure of Some Matrix Manifolds](https://openreview.net/forum?id=eyE9Fb2AvOT) NeurIPS 2022
- [Building Neural Networks on Matrix Manifolds: A Gyrovector Space Approach](https://arxiv.org/abs/2305.04560) ICML 2023
- [Matrix Manifold Neural Networks++](https://openreview.net/forum?id=30aSE3FB3L) iclr 2024
- [A Lie Group Approach to Riemannian Batch Normalization](https://openreview.net/forum?id=okYdj8Ysru) ICLR 2024
- [RMLR: Extending Multinomial Logistic Regression into General Geometries](https://arxiv.org/abs/2409.19433) NeurIPS 2024
- [Gyrogroup Batch Normalization](https://openreview.net/forum?id=d1NWq4PjJW) ICLR 2025
- [Neural Networks on Symmetric Spaces of Noncompact Type](https://openreview.net/forum?id=bwOndfohRK&noteId=XBiz6RG96t) ICLR 2025

## Applications in Euclidean Deep Learning

### High-order Pooling
- [Kernel Pooling for Convolutional Neural Networks](https://openaccess.thecvf.com/content_cvpr_2017/html/Cui_Kernel_Pooling_for_CVPR_2017_paper.html) CVPR 2017
- [Towards Faster Training of Global Covariance Pooling Networks by Iterative Matrix Square Root Normalization](https://arxiv.org/abs/1712.01034) CVPR 2018
- [DeepKSPD: Learning Kernel-matrix-based SPD  Representation for Fine-grained Image Recognition] ECCV 2018
- [Deep CNNs Meet Global Covariance Pooling: Better Representation and Generalization](https://arxiv.org/abs/1904.06836) TPAMI 2020
- [Learning partial correlation based deep visual representation for image classification](https://arxiv.org/abs/2304.11597) CVPR 2023
- [Understanding Matrix Function Normalizations in Covariance Pooling through the Lens of Riemannian Geometry](https://openreview.net/forum?id=q1t0Lmvhty) ICLR 2025