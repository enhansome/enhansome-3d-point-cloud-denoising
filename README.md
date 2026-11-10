# Awesome 3D Point Cloud Denoising with stars

Point cloud denoising and closely related 3D surface processing papers.

> \[!NOTE]
> We focus particularly on point clouds as a representation of 3D data and on denoising as a technique, but we also include some works that deal with other representations, such as meshes, voxels... or closely related techniques, such as hole-filling, surface reconstruction... since—like denoising—they aim to recover the underlying surface of the scanned real-world object.

This is a work in *continuous progress*.

For any suggestions, please contact <garnungalejandro@gmail.com>.

Thank you and enjoy the 3D point cloud denoising world.

**Updated: 21/09/2026**

## Contents

* [2003](#2003)
* [2006](#2006)
* [2007](#2007)
* [2008](#2008)
* [2009](#2009)
* [2010](#2010)
* [2011](#2011)
* [2012](#2012)
* [2013](#2013)
* [2014](#2014)
* [2015](#2015)
* [2016](#2016)
* [2017](#2017)
* [2018](#2018)
* [2019](#2019)
* [2020](#2020)
* [2021](#2021)
* [2022](#2022)
* [2023](#2023)
* [2024](#2024)
* [2025](#2025)
* [2026](#2026)

<h2>Keywords</h2>

`trad.`: traditional filter | `var.`: variational-based | `pde`: PDE-based | `spec.`: spectral-based | `dl.`: deep learning | `un.`: unsupervised | `rec.`: resampling/compression | `sur.`: surface reconstruction  | `ne.`: normal estimation | `inp.`: inpainting | `res.`: super-resolution | `mesh.`: mesh denoising | `surv.`: survey | `oth.`: other

Citation gradations: ◼️ Less than 5 citations · 🔹 More than 5 citations · 🔸 More than 10 citations · 🔥 More than 25 citations · 🌟 More than 50 citations.

## 2003

* [Bilateral mesh denoising](https://dev.ipol.im/~morel/Dossier_MVA_2011_Cours_Transparents_Documents/2011_Cours3_Document1_bilateral_mesh_denoising.pdf) - Traditional filter. [Code](https://github.com/bldeng/GuidedDenoising/tree/master) ⭐ 217 | 🐛 8 | 🌐 C++ | 📅 2020-06-13 `trad.` 🔸
* [Non-Iterative, Feature-Preserving Mesh Smoothing](https://people.csail.mit.edu/thouis/JDD03.pdf) - Mesh denoising, Traditional filter. [Code](https://github.com/Oponn-1/3D-Point-Cloud-Denoising/blob/master/smoother.c) ⭐ 9 | 🐛 1 | 🌐 C | 📅 2018-12-11 `mesh.` `trad.` 🔥
* [Mesh-Independent Surface Interpolation MLS](https://graphics.stanford.edu/courses/cs468-03-fall/Papers/Levin_MovingLeastSquares.pdf) - Other. `oth.` 🔥

## 2006

* [Point cloud denoising using robust principal component analysis](https://www.scitepress.org/papers/2006/13589/13589.pdf) - Traditional filter. `trad.` ◼️

## 2007

* [Fast and Effective Feature-Preserving Mesh Denoising](https://langbein.org/wp-content/uploads/2009/06/sun2007.pdf) - Mesh denoising, Traditional filter. [Code](https://github.com/bldeng/GuidedDenoising/tree/master) ⭐ 217 | 🐛 8 | 🌐 C++ | 📅 2020-06-13 `mesh.` `trad.` 🌟
* [Discrete Regularization on Weighted Graphs for Image and Mesh Filtering](https://hal.science/hal-00333374/file/SSVM-2007.pdf) - Variational-based method, PDE-based method, Mesh denoising. `var.` `pde` `mesh.` ◼️
* [Parameterization-free Projection for Geometry Reconstruction (LOP)](https://dev.ipol.im/~morel/Dossier_MVA_2011_Cours_Transparents_Documents/2011_Cours3_Document2_Locally_Optimal_Projection.pdf) - Resampling/compression, Surface reconstruction. `rec.` `sur.` 🔥

## 2008

* [Nonlocal discrete regularization on weighted graphs: A framework for image and manifold processing](https://lezoray.users.greyc.fr/Publis/IEEE_IP_2008.pdf) - Variational-based method. `var.` 🔥

## 2009

* [Consolidation of Unorganized Point Clouds for Surface Reconstruction (WLOP)](https://www.cs.sfu.ca/~haoz/pubs/siga09_consolidater_reduced.pdf) - Resampling/compression. [Code](https://github.com/jinseokbae/WLOP-based-PointCloudDenoiser) ⭐ 26 | 🐛 0 | 🌐 MATLAB | 📅 2021-02-01 `rec.` 🌟
* [Noise reduction and modeling methods of TLS point cloud based on R-tree](https://ieeexplore.ieee.org/document/5137578) - Traditional filter. `trad.` ◼️
* [Algorithm for 3D Point Cloud Denoising](https://ieeexplore.ieee.org/document/5402768) - Traditional filter. `trad.` ◼️
* [3D Body Point Cloud Data Denoising and Registration](https://ieeexplore.ieee.org/document/5287748) - Traditional filter. `trad.` ◼️

## 2010

* [Scatter Point Cloud Denoising Based on Self-Adaptive Optimal Neighborhood](https://www.scientific.net/AMR.97-101.3631) - Traditional filter. `trad.` ◼️
* [ℓ1-Sparse reconstruction of sharp point set surfaces](https://dl.acm.org/doi/10.1145/1857907.1857911) - Variational-based method. `var.` 🔹
* [Point Cloud Non Local Denoising Using Local Surface Descriptor Similarity](https://minesparis-psl.hal.science/hal-01097420/document) - Traditional filter. `trad.` 🌟

## 2011

* [Bilateral Normal Filtering for Mesh Denoising](https://hongbofu.people.ust.hk/doc/bilateral_normal_filtering_tvcg11.pdf) - Traditional filter, Mesh denoising. [Code](https://github.com/bldeng/GuidedDenoising/tree/master) ⭐ 217 | 🐛 8 | 🌐 C++ | 📅 2020-06-13 `trad.` `mesh.` 🌟
* [Nonlocal PDEs-Based Morphology on Weighted Graphs for Image and Data Processing](https://chpc.greyc.fr/images/Documents/Publications/2011_06_Nonlocal_PDEs-Based_Morphology_on_Weighted_Graphs_for_Image_and_Data_Processing.pdf) - PDE-based method. `pde` ◼️

## 2012

* [Denoising point cloud](https://www.tandfonline.com/doi/epdf/10.1080/17415977.2011.603087?needAccess=true) - Traditional filter. `trad.` ◼️
* [A New near Point Denoising Algorithm for Point Cloud](https://www.scientific.net/AMR.479-481.2152) - Traditional filter. `trad.` ◼️

## 2013

* [Mesh Denoising via L0 Minimization](https://people.engr.tamu.edu/schaefer/research/L0Smoothing.pdf) - Variational-based method, Mesh denoising. [Code](https://github.com/tatsy/L0Denoising) ⭐ 22 | 🐛 0 | 🌐 C++ | 📅 2016-06-03 [Code](https://github.com/AlonzoQuio/MeshDenoisingViaL0Minimization/tree/master) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2018-03-06 [Code](https://github.com/bldeng/GuidedDenoising/tree/master) ⭐ 217 | 🐛 8 | 🌐 C++ | 📅 2020-06-13 `var.` `mesh.` 🔥
* [Motion estimation and filtered prediction for dynamic point cloud attribute compression](https://par.nsf.gov/servlets/purl/10443276) - Resampling/compression. `rec.` ◼️
* [Edge-aware point set resampling (AWLOP/EAR)](https://dl.acm.org/doi/10.1145/2421636.2421645) - Resampling/compression. `rec.` 🔥

## 2014

* [A General Framework for Bilateral and Mean Shift Filtering](https://people.csail.mit.edu/jsolomon/assets/MeshBilateral.pdf) - Traditional filter. `trad.` ◼️
* [Research on 3D scanning point cloud de-nosing](https://ieeexplore.ieee.org/abstract/document/7009913) - Traditional filter. `trad.` ◼️
* [Continuous projection for fast L1 reconstruction (CLOP)](https://dl.acm.org/doi/10.1145/2601097.2601172) - Resampling/compression, Surface reconstruction. `rec.` `sur.` 🔸
* [State of the Art in Surface Reconstruction from Point Clouds](https://inria.hal.science/hal-01017700/file/star_author.pdf) - Survey, Surface reconstruction. `surv.` `sur.` 🌟

## 2015

* [Guided Mesh Normal Filtering](http://sofienbouaziz.com/pdf/GuidedFilter_PG15.pdf) - Mesh denoising, Normal estimation. [Code](https://github.com/bldeng/GuidedDenoising/tree/master) ⭐ 217 | 🐛 8 | 🌐 C++ | 📅 2020-06-13 `mesh.` `ne.` 🔥
* [Denoising Point Sets via L0 Minimization](https://www.sciencedirect.com/science/article/abs/pii/S0167839615000345) - Variational-based method. `var.` 🔸
* [3D point cloud denoising and normal estimation for 3D surface reconstruction](https://ieeexplore.ieee.org/document/7418871) - Traditional filter, Normal estimation. `trad.` `ne.` ◼️
* [Adaptive Denoising Algorithm for Scanning Beam Points Based on Angle Thresholds](https://www.scientific.net/AMM.741.204) - Traditional filter. `trad.` ◼️
* [Graph-based denoising for time varying point clouds](https://arxiv.org/pdf/1511.04902) - Variational-based method. `var.` ◼️
* [Variational Mesh Denoising Using Total Variation and Piecewise Constant Function Space](https://doi.org/10.1109/TVCG.2015.2398432) - Variational-based method, Mesh denoising. `var.` `mesh.` 🌟

## 2016

* [Density-based Denoising of Point Cloud](https://arxiv.org/pdf/1602.05312) - Traditional filter. `trad.` ◼️
* [Mesh Denoising via Cascaded Normal Regression](https://dl.acm.org/doi/10.1145/2980179.2980232) - Mesh denoising. `mesh.` 🔥
* [Point Cloud Noise and Outlier Removal for Image-Based 3D Reconstruction](https://ieeexplore.ieee.org/document/7785084) - Traditional filter. `trad.` ◼️
* [Dynamic occlusion detection and inpainting of in situ captured terrestrial laser scanning point clouds sequence](https://www.sciencedirect.com/science/article/abs/pii/S0924271616300922) - Inpainting. `inp.` ◼️
* [Robust Feature-Preserving Denoising of 3D Point Clouds](https://ee.iisc.ac.in/cvlab/papers/haque2016robden.pdf) - Traditional filter. `trad.` ◼️

## 2017

* [Guided 3D point cloud filtering](https://link.springer.com/article/10.1007/s11042-017-5310-9) - Traditional filter. [Code](https://github.com/aipiano/guided-filter-point-cloud-denoise) ⭐ 97 | 🐛 2 | 🌐 Python | 📅 2019-05-07 `trad.` ◼️
* [Point Cloud Denoising via Moving RPCA](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13068) - Traditional filter, Variational-based method. `trad.` `var.` 🔸
* [The bilateral filter for point clouds](https://www.ipol.im/pub/art/2017/179/revisions/2022-01-01/article.pdf) - Traditional filter. [Code](https://www.ipol.im/pub/art/2017/179/) `trad.` 🔹
* [Hierarchical Denoising Method of Crop 3D Point Cloud Based on Multi-view Image Reconstruction](https://inria.hal.science/hal-02124225v1/document) - Traditional filter. `trad.` ◼️
* [Data-Driven Sparse Priors of 3D Shapes](https://onlinelibrary.wiley.com/doi/10.1111/cgf.13272) - Variational-based method. `var.` ◼️
* [Guided point cloud denoising via sharp feature skeletons](https://link.springer.com/article/10.1007/s00371-017-1391-8) - Traditional filter. `trad.` ◼️

## 2018

* [EC-Net: an Edge-aware Point set Consolidation Network](https://yulequan.github.io/ec-net/index.html) - Deep learning, Resampling/compression. [Code](https://github.com/yulequan/EC-Net) ⭐ 106 | 🐛 3 | 🌐 Python | 📅 2022-04-07 `dl.` `rec.` 🔥
* [Static/Dynamic Filtering for Mesh Geometry](https://arxiv.org/pdf/1712.03574) - Mesh denoising, Traditional filter. [Code](https://github.com/bldeng/MeshSDFilter) ⭐ 62 | 🐛 3 | 🌐 C++ | 📅 2020-08-13 `mesh.` `trad.` ◼️
* [DUP-Net: Denoiser and Upsampler Network for 3D Adversarial Point Clouds Defense](http://staff.ustc.edu.cn/~zhangwm/Paper/2019_12.pdf) - Deep learning, Resampling/compression. [Code](https://github.com/RyanHangZhou/tensorflow-DUP-Net) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2021-08-10 `dl.` `rec.` 🔥
* [Fast 3D Point Cloud Denoising via Bipartite Graph Approximation & Total Variation](https://arxiv.org/pdf/1804.10831) - Variational-based method. `var.` ◼️
* [Weighted Multi-projection: 3D Point Cloud Denoising with Estimated Tangent Planes](https://arxiv.org/pdf/1807.00253) - Traditional filter. `trad.` ◼️
* [Pointpronets: Consolidation of point clouds with convolutional neural networks](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13344) - Deep learning, Resampling/compression. `dl.` `rec.` 🔹
* [Robust and effective mesh denoising using L0 sparse regularization](https://www3.cs.stonybrook.edu/~qin/research/2018-cad-mesh-denoising-using-sparse-regularization.pdf) - Mesh denoising, Variational-based method. `mesh.` `var.` ◼️
* [Constraint based point set denoising using normal voting tensor and restricted quadratic error metrics](https://www.sciencedirect.com/science/article/abs/pii/S0097849318300797) - Traditional filter, Normal estimation. `trad.` `ne.` ◼️
* [Denoising of point cloud data for computer-aided design, engineering, and manufacturing](https://link.springer.com/article/10.1007/s00366-017-0556-4) - Survey. `surv.` 🔥
* [3D Point Cloud Denoising via Bipartite Graph Approximation and Reweighted Graph Laplacian](https://arxiv.org/pdf/1812.07711) - Variational-based method. `var.` ◼️
* [3D Shape Processing by Convolutional Denoising Autoencoders on Local Patches](https://ieeexplore.ieee.org/document/8354317) - Deep learning. `dl.` ◼️
* [De-noising of Lidar Point Clouds Corrupted by Snowfall](https://doi.org/10.1109/CRV.2018.00043) - Traditional filter. `trad.` 🌟
* [DDRNet: Depth Map Denoising and Refinement for Consumer Depth Cameras Using Cascaded CNNs](https://doi.org/10.1007/978-3-030-01249-6_10) - Deep learning. `dl.` 🌟
* [Non-Local Low-Rank Normal Filtering for Mesh Denoising](https://doi.org/10.1111/cgf.13556) - Mesh denoising, Normal estimation. `mesh.` `ne.` 🌟

## 2019

* [Differentiable Surface Splatting for Point-based Geometry Processing](https://arxiv.org/pdf/1906.04173) - Resampling/compression, Deep learning. [Code](https://github.com/yifita/DSS) ⭐ 446 | 🐛 12 | 🌐 Python | 📅 2026-04-13 `rec.` `dl.` 🔸
* [PointCleanNet: Learning to Denoise and Remove Outliers from Dense Point Clouds](https://arxiv.org/pdf/1901.01060) - Deep learning. [Code](https://github.com/mrakotosaon/pointcleannet) ⭐ 293 | 🐛 2 | 🌐 Python | 📅 2020-07-29 `dl.` 🌟
* [Total denoising: Unsupervised learning of 3D point cloud cleaning (TD)](https://arxiv.org/pdf/1904.07615) - Unsupervised learning. [Code](https://github.com/phermosilla/TotalDenoising) ⚠️ Archived `un.` 🔸
* [3D Point Cloud Denoising using Graph Laplacian Regularization of a Low Dimensional Manifold Model](https://arxiv.org/pdf/1803.07252) - Variational-based method. [Code](https://github.com/jzengust/ldmm_graph_laplacian_pointcloud_denoise) ⭐ 40 | 🐛 1 | 🌐 MATLAB | 📅 2019-12-20 `var.` 🔸
* [Deep Unsupervised Learning of 3D Point Clouds via Graph Topology Inference and Filtering](https://www.semanticscholar.org/paper/Deep-Unsupervised-Learning-of-3D-Point-Clouds-via-Chen-Duan/4d941083fa57d62fed269ceecbf7d8af66ec6c9c) - Unsupervised learning. [Code](https://github.com/merlresearch/FoldingNet_Plus) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2023-09-14 `un.` 🔹
* [A 3D point cloud filtering method for leaves based on manifold distance and normal estimation](https://www.mdpi.com/2072-4292/11/2/198) - Traditional filter, Normal estimation. `trad.` `ne.` ◼️
* [3D Point Cloud Denoising via Deep Neural Network based Local Surface Estimation](https://arxiv.org/pdf/1904.04427) - Deep learning. `dl.` ◼️
* [A Novel Denoising Algorithm for Airborne Lidar Point Cloud Based on Empirical Mode Decomposition](https://isprs-archives.copernicus.org/articles/XLII-2-W13/1021/2019/isprs-archives-XLII-2-W13-1021-2019.pdf) - Traditional filter. `trad.` ◼️
* [A 3D Point Cloud Filtering Algorithm based on Surface Variation Factor Classification](https://www.sciencedirect.com/science/article/pii/S1877050919307793) - Traditional filter. `trad.` ◼️
* [Low Rank Matrix Approximation for 3D Geometry Filtering](https://people.engr.tamu.edu/schaefer/research/low_rank.pdf) - Variational-based method. `var.` ◼️
* [Method for Filtering Dense Noise from Laser Scanning Data](https://m.researching.cn/articles/OJe0757400bd253676/referenceandcitations) - Traditional filter. `trad.` ◼️
* [Denoising of 3D point clouds constructed from light fields](https://ieeexplore.ieee.org/document/8683548) - Deep learning. `dl.` ◼️
* [A novel anisotropic second order regularization for mesh denoising](https://www.sciencedirect.com/science/article/abs/pii/S0167839619300299) - Variational-based method, Mesh denoising. `var.` `mesh.` ◼️
* [Denoising of 3D Point clouds](https://isprs-archives.copernicus.org/articles/XLII-2-W17/217/2019/) - Traditional filter. `trad.` ◼️
* [3D Point Cloud Color Denoising Using Convex Graph-Signal Smoothness Priors](https://ieeexplore.ieee.org/document/8901695) - Variational-based method. `var.` ◼️
* [Self-Supervised Deep Depth Denoising](https://arxiv.org/abs/1909.01193) - Deep learning, Unsupervised learning. `dl.` `un.` 🔥

## 2020

* [CNN-based Lidar Point Cloud De-Noising in Adverse Weather](https://arxiv.org/pdf/1912.03874) - Deep learning. [Code](https://github.com/rheinzler/PointCloudDeNoising) ⭐ 136 | 🐛 6 | 🌐 Python | 📅 2022-06-22 `dl.` 🔸
* [Differentiable Manifold Reconstruction for Point Cloud Denoising](https://arxiv.org/pdf/2007.13551) - Unsupervised learning. [Code](https://github.com/luost26/DMRDenoise) ⚠️ Archived `un.` 🔸
* [Pointfilter: Point Cloud Filtering via Encoder Decoder Modeling](https://arxiv.org/pdf/2002.05968) - Deep learning. [Code](https://github.com/dongbo-BUAA-VR/Pointfilter) ⭐ 70 | 🐛 10 | 🌐 Python | 📅 2021-09-24 `dl.` 🔹
* [Learning Graph-Convolutional Representations for Point Cloud Denoising (GPDNet)](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650103.pdf) - Deep learning. [Code](https://github.com/diegovalsesia/GPDNet) ⭐ 32 | 🐛 7 | 🌐 Python | 📅 2020-07-03 `dl.` 🔹
* [Deep Point Set Resampling via Gradient Fields](https://arxiv.org/pdf/2111.02045) - Deep learning, Resampling/compression. [Code](https://github.com/ChenhLiwnl/deep-rs) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2022-06-19 `dl.` `rec.` 🔹
* [Mesh Denoising with Facet Graph Convolutions](https://ieeexplore.ieee.org/document/9296808) - Deep learning, Mesh denoising. [Code](https://github.com/Elensil/Facet_Graph_Convolution) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2022-02-14 `dl.` `mesh.` 🔹
* [Feature Graph Learning for 3D Point Cloud Denoising (FGL)](https://ieeexplore.ieee.org/document/9026751) - Variational-based method. `var.` ◼️
* [Point Cloud Denoising via Feature Graph Laplacian Regularization](https://ieeexplore.ieee.org/document/8976421) - Variational-based method. `var.` ◼️
* [Non-Local Part-Aware Point Cloud Denoising](https://arxiv.org/pdf/2003.06631) - Deep learning. `dl.` ◼️
* [Research on denoising algorithm of 3D point cloud data based on curvature change](https://iopscience.iop.org/article/10.1088/1757-899X/768/7/072041/pdf) - Traditional filter. `trad.` ◼️
* [Point Cloud Denoising Algorithm Based on Noise Classification](https://www.computer.org/csdl/proceedings-article/iccst/2020/813800a123/1p1gtJQEUPC) - Traditional filter. `trad.` ◼️
* [Learning robust graph-convolutional representations for point cloud denoising](https://ieeexplore.ieee.org/document/9309029) - Deep learning. `dl.` ◼️
* [3D point cloud registration denoising method for human motion image using deep learning algorithm](https://www.researchgate.net/publication/334846348_3D_point_cloud_registration_denoising_method_for_human_motion_image_using_deep_learning_algorithm) - Deep learning. `dl.` ◼️
* [A feature-preserving framework for point cloud denoising](https://www.sciencedirect.com/science/article/abs/pii/S0010448520300506) - Traditional filter, Variational-based method. `trad.` `var.` ◼️
* [Sparse Regularization-Based Approach for Point Cloud Denoising and Sharp Features Enhancement](https://www.mdpi.com/1424-8220/20/11/3206) - Variational-based method. `var.` ◼️
* [Deep feature-preserving normal estimation for point cloud filtering](https://www.sciencedirect.com/science/article/abs/pii/S0010448520300531) - Deep learning, Normal estimation. `dl.` `ne.` ◼️
* [Deep Manifold Prior](https://arxiv.org/pdf/2004.04242) - Deep learning. `dl.` ◼️
* [Edge-guided second-order total generalized variation for Gaussian noise removal from depth map](https://www.researchgate.net/publication/345665258_Edge-guided_second-order_total_generalized_variation_for_Gaussian_noise_removal_from_depth_map) - Variational-based method. `var.` 🔹
* [Noise-robust transparent visualization of large-scale point clouds acquired by laser scanning](https://www.sciencedirect.com/science/article/pii/S0924271620300046) - Other. `oth.` ◼️
* [3D Point Cloud Denoising Using a Joint Geometry and Color k-NN Graph](https://ieeexplore.ieee.org/document/9287341) - Variational-based method. `var.` ◼️
* [Dynamic Point Cloud Denoising via Manifold-to Manifold Distance](https://ieeexplore.ieee.org/document/9472930) - Variational-based method. `var.` ◼️
* [Fast and Accurate Desnowing Algorithm for LiDAR Point Clouds](https://doi.org/10.1109/ACCESS.2020.3020266) - Traditional filter. `trad.` 🌟

## 2021

* [Score-Based Point Cloud Denoising](https://openaccess.thecvf.com/content/ICCV2021/papers/Luo_Score-Based_Point_Cloud_Denoising_ICCV_2021_paper.pdf) - Unsupervised learning. [Code](https://github.com/luost26/score-denoise) ⚠️ Archived `un.` 🔥
* [RePCD-Net: Feature-Aware Recurrent Point Cloud Denoising Network](https://link.springer.com/article/10.1007/s11263-021-01564-7) - Deep learning. [Code](https://github.com/chenhonghua/RePCD-Net) ⭐ 26 | 🐛 2 | 🌐 Python | 📅 2024-03-03 `dl.` ◼️
* [VIPDA: A Visually Driven Point Cloud Denoising Algorithm Based on Anisotropic Point Cloud Filtering](https://www.frontiersin.org/journals/signal-processing/articles/10.3389/frsip.2022.842570/full) - Traditional filter. `trad.` ◼️
* [Mesh Total Generalized Variation for Denoising](https://arxiv.org/pdf/2101.02322) - Variational-based method, Mesh denoising. `var.` `mesh.` ◼️
* [Exploiting color for graph-based 3D point cloud denoising](https://www.sciencedirect.com/science/article/pii/S1047320321000092?dgcid=raven_sd_recommender_email) - Variational-based method. `var.` ◼️
* [PCA-Based Denoising Algorithm for Outdoor Lidar Point Cloud Data](https://www.mdpi.com/1424-8220/21/11/3703?https://susy.mdpi.com/\&gad_source=1\&gclid=Cj0KCQiAst67BhCEARIsAKKdWOkK_otZ43ufvO6Hu8fxvQGBWk5pM4ZK54YxdwhDntGlqbAJJBCE-GQaAlkgEALw_wcB) - Traditional filter. `trad.` ◼️
* [Anisotropic Denoising of 3D Point Clouds by Aggregation of Multiple Surface-Adaptive Estimates](https://webpages.tuni.fi/foi/papers/Anisotropic_Denoising_of_3D_Point_Clouds_by_Aggregation_of_Multiple_Surface_Adaptive_Estimates-prepress.pdf) - Traditional filter. `trad.` ◼️
* [Joint Geometry and Color Point Cloud Denoising Based on Graph Wavelets](https://ieeexplore.ieee.org/document/9334993) - Spectral-based method. `spec.` ◼️
* [Point cloud denoising using non-local collaborative projections](https://www.sciencedirect.com/science/article/abs/pii/S0031320321003150) - Traditional filter. `trad.` ◼️
* [DSOR: A Scalable Statistical Filter for Removing Falling Snow from LiDAR Point Clouds in Severe Winter Weather](https://arxiv.org/abs/2109.07078) - Traditional filter. `trad.` 🔥

## 2022

* [PD-Flow: A Point Cloud Denoising Framework with Normalizing Flows](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136630392.pdf) - Deep learning. [Code](https://github.com/unknownue/pdflow) ⭐ 31 | 🐛 2 | 🌐 Python | 📅 2022-08-11 `dl.` ◼️
* [MODNet: Multi-offset Point Cloud Denoising Network Customized for Multi-scale Patches](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14661) - Deep learning. [Code](https://github.com/hay-001/MODNet) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2023-02-22 `dl.` ◼️
* [Structure-Aware Denoising for Real-world Noisy Point Clouds with Complex Structures](https://www.semanticscholar.org/paper/Structure-Aware-Denoising-for-Real-world-Noisy-with-Sun-Chu/5da3a477363e6a3f303b5402dbe62011deb53a4f) - Deep learning. [Code](https://github.com/rg089/SCANING) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2023-08-19 `dl.` ◼️
* [Single-Stage Adaptive Multi-Scale Point Cloud Noise Filtering Algorithm Based on Feature Information](https://www.mdpi.com/2072-4292/14/2/367) - Traditional filter. `trad.` ◼️
* [GeoGCN: Geometric Dual-domain Graph Convolution Network for Point Cloud Denoising](https://arxiv.org/pdf/2210.15913) - Deep learning. `dl.` ◼️
* [TDNet: transformer-based network for point cloud denoising](https://caoxin918.github.io/files/%E5%BE%90%E9%9B%AA%E4%B8%BDAO.pdf) - Deep learning. `dl.` ◼️
* [Point cloud denoising algorithm with geometric feature preserving](https://link.springer.com/article/10.1007/s00530-022-00936-4) - Traditional filter. `trad.` ◼️
* [Point Cloud Upsampling Algorithm: A Systematic Review](https://www.mdpi.com/1999-4893/15/4/124) - Survey. `surv.` ◼️
* [Dynamic Point Cloud Denoising via Gradient Fields](https://www.semanticscholar.org/reader/524b518d34a672f8f84ba7b139aff00b763464d0) - Deep learning. `dl.` ◼️
* [From Noise Addition to Denoising: A Self-Variation Capture Network for Point Cloud Optimization](https://ieeexplore.ieee.org/document/9998112) - Deep learning. `dl.` ◼️
* [Point cloud denoising review: from classical to deep learning-based approaches](https://www.sciencedirect.com/science/article/abs/pii/S1524070322000170) - Survey. `surv.` 🌟
* [Denoising for 3D Point Cloud Based on Regularization of a Statistical Low-Dimensional Manifold](https://www.mdpi.com/1424-8220/22/7/2666) - Variational-based method. `var.` ◼️
* [Reflective Noise Filtering of Large-Scale Point Cloud Using Transformer](https://www.mdpi.com/2072-4292/14/3/577) - Deep learning. `dl.` ◼️
* [Optimization of point cloud preprocessing algorithm for equipped vehicles](https://iopscience.iop.org/article/10.1088/1742-6596/2383/1/012080/pdf) - Traditional filter. `trad.` ◼️
* [LiSnowNet: Real-time Snow Removal for LiDAR Point Cloud](https://arxiv.org/abs/2211.10023) - Deep learning, Unsupervised learning. `dl.` `un.` ◼️
* [Comprehensive Review of Deep Learning-Based 3D Point Cloud Completion Processing and Analysis](https://arxiv.org/pdf/2203.03311) - Survey. `surv.` 🔹
* [A Method Based on Improved iForest for Trunk Extraction and Denoising of Individual Street Trees](https://www.mdpi.com/2072-4292/15/1/115) - Traditional filter. `trad.` ◼️
* [A Scalable and Accurate De-Snowing Algorithm for LiDAR Point Clouds in Winter](https://doi.org/10.3390/rs14061468) - Traditional filter. `trad.` 🌟

## 2023

* [IterativePFN: True Iterative Point Cloud Filtering](https://openaccess.thecvf.com/content/CVPR2023/papers/de_Silva_Edirimuni_IterativePFN_True_Iterative_Point_Cloud_Filtering_CVPR_2023_paper.pdf) - Deep learning. [Code](https://github.com/ddsediri/IterativePFN) ⭐ 69 | 🐛 2 | 🌐 Python | 📅 2023-08-23 `dl.` ◼️
* [4DenoiseNet: Adverse Weather Denoising From Adjacent Point Clouds](https://arxiv.org/pdf/2209.07121) - Deep learning. [Code](https://github.com/alvariseppanen/4DenoiseNet) ⚠️ Archived `dl.` ◼️
* [Point Cloud Denoising via Momentum Ascent in Gradient Fields](https://arxiv.org/pdf/2202.10094) - Deep learning. [Code](https://github.com/IndigoPurple/MAG) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2024-10-08 `dl.` ◼️
* [PCDNF: Revisiting Learning-based Point Cloud Denoising via Joint Normal Filtering](https://ieeexplore.ieee.org/document/10173632) - Deep learning, Normal estimation. [Code](https://github.com/LabZhengLiu/PCDNF) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2023-08-04 `dl.` `ne.` ◼️
* [Contrastive Learning for Joint Normal Estimation and Point Cloud Filtering](https://arxiv.org/pdf/2208.06811) - Deep learning, Normal estimation. [Code](https://github.com/ddsediri/CLJNEPCF) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2023-08-24 `dl.` `ne.` ◼️
* [Refine-Net: Normal Refinement Neural Network for Noisy Point Clouds](https://ieeexplore.ieee.org/document/9693131) - Deep learning, Normal estimation. [Code](https://github.com/hrzhou2/refinenet) ⭐ 8 | 🐛 3 | 🌐 C++ | 📅 2022-04-09 `dl.` `ne.` ◼️
* [Point Cloud Denoising Algorithm via Geometric Metrics on the Statistical Manifold](https://www.semanticscholar.org/paper/Point-Cloud-Denoising-Algorithm-via-Geometric-on-Duan-Feng/0deb0dd5f748b350943c538c53cc11fdbc33fe78) - Traditional filter. `trad.` ◼️
* [3D Point Cloud Denoising Algorithm Based on Two-Stage Filtering](https://ieeexplore.ieee.org/document/10226976) - Traditional filter. `trad.` ◼️
* [Attention Mechanism-based Deep Learning Denoising of Scanned Point Cloud for Rocket Tank Panel](https://www.researchgate.net/publication/377903007_Attention_Mechanism-Based_Deep_Learning_Denoising_of_Scanned_Point_Cloud_for_Rocket_Tank_Panel) - Deep learning. `dl.` ◼️
* [NoiseTrans: Point Cloud Denoising with Transformers](https://arxiv.org/pdf/2304.11812) - Deep learning. `dl.` ◼️
* [A single-stage point cloud cleaning network for outlier removal and denoising](https://www.sciencedirect.com/science/article/pii/S0031320323000675?dgcid=raven_sd_recommender_email) - Deep learning. `dl.` ◼️
* [GeoDualCNN: Geometry Supporting Dual Convolutional Neural Network for Noisy Point Clouds](https://ieeexplore.ieee.org/document/9543583) - Deep learning. `dl.` ◼️
* [DMNR: Unsupervised De-noising of Point Clouds Corrupted by Airborne Particles](https://arxiv.org/abs/2305.05991) - Deep learning, Unsupervised learning. `dl.` `un.` ◼️
* [MSaD-Net: A Mix Self-Attention Networks for 3D Point Cloud Denoising](https://ieeexplore.ieee.org/document/10114488) - Deep learning. `dl.` ◼️
* [Parameter optimization for point clouds denoising based on no-reference quality assessment](https://www.sciencedirect.com/science/article/abs/pii/S0263224123001562) - Traditional filter. `trad.` ◼️
* [Multiscale Feature Fusion for the Multistage Denoising of Airborne Single Photon LiDAR](https://www.mdpi.com/2072-4292/15/1/269) - Traditional filter. `trad.` ◼️
* [Bilateral filter denoising of Lidar point cloud data in automatic driving scene](https://www.sciencedirect.com/science/article/pii/S1350449523001822) - Traditional filter. `trad.` ◼️
* [3D point cloud global denoising algorithm based on different noise characteristics](https://iopscience.iop.org/article/10.1088/1361-6501/ad044d) - Traditional filter. `trad.` ◼️
* [3D point cloud denoising using anisotropic neighborhoods and a novel sharp feature detection algorithm](https://link.springer.com/article/10.1007/s00371-022-02698-6) - Traditional filter. [Code](https://git.tecgraf.puc-rio.br/hurtado/point_cloud_denoising_tvcj) `trad.` ◼️
* [A Noising-Denoising Framework for Point Cloud Upsampling via Normalizing Flows](https://dl.acm.org/doi/abs/10.1016/j.patcog.2023.109569) - Deep learning, Super-resolution. `dl.` `res.` ◼️
* [TP-NoDe: Topology-aware Progressive Noising and Denoising of Point Clouds towards Upsampling](https://www.researchgate.net/publication/376817692_TP-NoDe_Topology-aware_Progressive_Noising_and_Denoising_of_Point_Clouds_towards_Upsampling) - Deep learning, Super-resolution. `dl.` `res.` ◼️
* [Graph-Based Point Cloud Color Denoising with 3-Dimensional Patch-Based Similarity](https://ieeexplore.ieee.org/document/10095488) - Variational-based method. `var.` ◼️
* [Deep learning-based point cloud upsampling: a review of recent trends](https://link.springer.com/article/10.1007/s42791-023-00058-6) - Survey. `surv.` ◼️
* [3D point cloud denoising method based on global feature guidance](https://link.springer.com/article/10.1007/s00371-023-03158-5) - Deep learning. `dl.` ◼️
* [Snow Removal for LiDAR Point Clouds With Spatio-Temporal Conditional Random Fields](https://doi.org/10.1109/LRA.2023.3311360) - Deep learning. `dl.` 🔸

## 2024

* [P2P-Bridge Diffusion Bridges for 3D Point Cloud](https://arxiv.org/pdf/2408.16325) - Deep learning. [Code](https://github.com/matvogel/P2P-Bridge) ⭐ 112 | 🐛 4 | 🌐 Python | 📅 2024-09-30 `dl.` ◼️
* [TripleMixer A 3D Point Cloud Denoising Model or Adverse Weather](https://arxiv.org/pdf/2408.13802) - Deep learning. [Code](https://github.com/Grandzxw/TripleMixer) ⭐ 80 | 🐛 6 | 🌐 Python | 📅 2026-04-14 `dl.` ◼️
* [PathNet: Path-Selective Point Cloud Denoising](https://3d.bk.tudelft.nl/liangliang/publications/2024/pathnet/PathNet.pdf) - Deep learning. [Code](https://github.com/ZeyongWei/PathNet) ⭐ 48 | 🐛 5 | 🌐 Python | 📅 2024-04-27 `dl.` ◼️
* [StraightPCF: Straight Point Cloud Filtering](https://arxiv.org/pdf/2405.08322) - Deep learning. [Code](https://github.com/ddsediri/StraightPCF) ⭐ 38 | 🐛 0 | 🌐 Python | 📅 2024-10-07 `dl.` ◼️
* [Denoising Point Clouds in Latent Space via Graph Convolution and Invertible Neural Network](https://openaccess.thecvf.com/content/CVPR2024/html/Mao_Denoising_Point_Clouds_in_Latent_Space_via_Graph_Convolution_and_CVPR_2024_paper.html) - Deep learning. [Code](https://github.com/yanbiao1/PD-LTS?tab=readme-ov-file) ⭐ 34 | 🐛 4 | 🌐 Python | 📅 2024-08-02 `dl.` ◼️
* [Self-supervised multi-echo point cloud denoising in snowfall](https://www.sciencedirect.com/science/article/pii/S0167865524002101) - Deep learning, Unsupervised learning. [Code](https://github.com/alvariseppanen/SMEDen) ⚠️ Archived `dl.` `un.` ◼️
* [PointCVaR: Risk-optimized Outlier Removal for Robust 3D Point Cloud Classification](https://arxiv.org/pdf/2307.10875) - Deep learning, Other. [Code](https://github.com/shinke-li/pointcvar) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2024-03-27 `dl.` `oth.` ◼️
* [Fast graph-based denoising point cloud color information](https://arxiv.org/pdf/2401.09721) - Variational-based method. `var.` ◼️
* [Three-Dimensional Point Cloud Denoising for Tunnel Data by Combining Intensity and Geometry Information](https://www.mdpi.com/2071-1050/16/5/2077) - Traditional filter. `trad.` ◼️
* [Point Cloud Denoising in Outdoor Real-World Scenes Based on Measurable Segmentation](https://www.mdpi.com/2072-4292/16/13/2347) - Deep learning. `dl.` ◼️
* [Transformer-based Point Cloud Denoising Network](https://ieeexplore.ieee.org/document/10303185) - Deep learning. `dl.` ◼️
* [3DMambaIPF: A State Space Model for Iterative Point Cloud Filtering via Differentiable Rendering](https://arxiv.org/abs/2404.05522v1) - Deep learning. `dl.` ◼️
* [The implementation method of point cloud denoising filter based on KinectV2](https://www.researchgate.net/publication/382355164_The_implementation_method_of_point_cloud_denoising_filter_based_on_KinectV2/fulltext/6699306c02e9686cd10d945b/The-implementation-method-of-point-cloud-denoising-filter-based-on-KinectV2.pdf) - Traditional filter. `trad.` ◼️
* [Hybrid Denoising Algorithm for Architectural Point Clouds Acquired with SLAM Systems](https://www.mdpi.com/2072-4292/16/23/4559) - Traditional filter. `trad.` ◼️
* [Denoising point clouds with fewer learnable parameters](https://www.sciencedirect.com/science/article/abs/pii/S0010448524000356) - Deep learning. `dl.` ◼️
* [Review of 3D Point Cloud Processing Methods Based on Deep Learning](https://www.researching.cn/articles/OJeb4150232c7fa1bc) - Survey. `surv.` ◼️
* [A Novel Point Cloud Adaptive Filtering Algorithm for LiDAR SLAMinForest Environments Based on Guidance Information](https://www.mdpi.com/2072-4292/16/15/2714) - Traditional filter. `trad.` ◼️
* [Deep Learning for 3D Point Cloud Enhancement: A Survey](https://arxiv.org/pdf/2411.00857) - Survey. `surv.` ◼️
* [TPDNet: A point cloud data denoising method for offshore drilling platforms and its application](https://www.sciencedirect.com/science/article/abs/pii/S0263224124015562) - Deep learning. `dl.` ◼️
* [Point Cloud Denoising With Fine-Granularity Dynamic Graph Convolutional Networks](https://arxiv.org/abs/2411.14158) - Deep learning. `dl.` ◼️
* [Noise4Denoise: Leveraging Noise for Unsupervised Point Cloud Denoising](https://link.springer.com/article/10.1007/s41095-024-0423-3) - Unsupervised learning. `un.` ◼️
* [3D-OutDet: A Fast and Memory Efficient Outlier Detector for 3D LiDAR Point Clouds in Adverse Weather](https://doi.org/10.1109/IV55156.2024.10588582) - Deep learning. `dl.` 🔸
* [A noise-reduction algorithm for raw 3D point cloud data of asphalt pavement surface texture](https://doi.org/10.1038/s41598-024-65233-8) - Traditional filter. `trad.` 🔸

## 2025

* [SuperPC: A Single Diffusion Model for Point Cloud Completion, Upsampling, Denoising, and Colorization](https://arxiv.org/pdf/2503.14558) - Deep learning, Super-resolution, Other. [Code](https://github.com/sair-lab/SuperPC) ⭐ 25 | 🐛 9 | 🌐 Python | 📅 2026-06-15 `dl.` `res.` `oth.` ◼️
* [You Should Learn to Stop Denoising on Point Clouds in Advance (ASDN)](https://ojs.aaai.org/index.php/AAAI/article/view/32331) - Deep learning. [Code](https://github.com/git-guocc/ASDN) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2025-09-28 `dl.` ◼️
* [Learning Normals of Noisy Points by Local Gradient-Aware Surface Filtering (LGSF)](https://openaccess.thecvf.com/content/ICCV2025/papers/Li_Learning_Normals_of_Noisy_Points_by_Local_Gradient-Aware_Surface_Filtering_ICCV_2025_paper.pdf) - Normal estimation, Deep learning. [Code](https://github.com/LeoQLi/LGSF) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2025-10-15 `ne.` `dl.` ◼️
* [Noise2Score3D: Tweedie's Approach for Unsupervised Point Cloud Denoising](https://arxiv.org/pdf/2503.09283) - Unsupervised learning, Deep learning. [Code](https://github.com/Bobby645/Noise2Score3D) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-06-24 `un.` `dl.` ◼️
* [LiDAR point cloud denoising for individual tree extraction based on the Noise4Denoise](https://www.frontiersin.org/journals/plant-science/articles/10.3389/fpls.2024.1490660/full) - Unsupervised learning. `un.` ◼️
* [Deep Learning For Point Cloud Denoising: A Survey](https://arxiv.org/pdf/2508.11932) - Survey, Deep learning. `surv.` `dl.` ◼️
* [A Survey of Deep Learning-based Point Cloud Denoising](https://arxiv.org/pdf/2508.17011) - Survey, Deep learning. `surv.` `dl.` ◼️
* [U-CAN: Unsupervised Point Cloud Denoising with Consistency-Aware Noise2Noise Matching](https://arxiv.org/pdf/2510.25210) - Unsupervised learning, Deep learning. [Code](https://gloriasze.github.io/U-CAN/) `un.` `dl.` ◼️

## 2026

* [SIMPC: Learning Self-Induced Mirror-Point Consistency for Unsupervised Point Cloud Denoising](https://arxiv.org/pdf/2605.26894) - Unsupervised learning, Deep learning. `un.` `dl.` ◼️
* [Routing on Demand: DSNet for Efficient Progressive Point Cloud Denoising](https://openaccess.thecvf.com/content/CVPR2026/papers/Cheng_Routing_on_Demand_DSNet_for_Efficient_Progressive_Point_Cloud_Denoising_CVPR_2026_paper.pdf) - Deep learning. [Code](https://github.com/cz-61/DSNet) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-08-12 `dl.` ◼️
* [Total Generalized Variation Based Point Cloud Denoising](https://doi.org/10.1016/j.cagd.2026.102622) - Variational-based method. `var.` ◼️
* [DeSnow-GNN: Spatiotemporal Graph Neural Network for Robust LiDAR Point Cloud Denoising in Adverse Weather](https://doi.org/10.1016/j.aei.2026.104449) - Deep learning. `dl.` ◼️
* [Deterministic Point Cloud Diffusion for Denoising](https://doi.org/10.1109/TVCG.2025.3621633) - Deep learning. `dl.` ◼️

<a href="https://www.star-history.com/#agarnung/awesome-3d-point-cloud-denoising&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=agarnung/awesome-3d-point-cloud-denoising&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=agarnung/awesome-3d-point-cloud-denoising&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=agarnung/awesome-3d-point-cloud-denoising&type=date&legend=top-left" />
 </picture>
</a>

## Footnotes

* Author's survey: [Unraveling Noise in 3D Point Clouds: A Comprehensive Survey](https://www.mdpi.com/2673-8244/6/4/70).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-10._
