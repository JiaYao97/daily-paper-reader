<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-26 ~ 2026-07-05
- 运行时间：2026-07-05 14:57:28 UTC
- 运行状态：成功
- 本次总论文数：21
- 精读区：8
- 速读区：13

### 今日简报（AI）
今日精读2篇9分论文：随机神经算子实现参数PDE快速训练与保形不确定性量化，物理感知神经算子变压器完成EAST偏滤器温度场重建；速读3篇8分论文涵盖潜在SDE可辨识性、世界模型路径空间公式与多尺度物理场自监督表征。最值得关注方向为随机神经算子（高效训练+不确定性量化）和物理感知神经算子变压器（工程应用）。建议读者深入神经算子方法与物理先验融合，关注其在工程模拟与稳健推断中的落地潜力。
- 详情：[/20260626-20260705/README](/20260626-20260705/README)

### 精读区论文标签
1. [Randomized neural operator for parametric PDEs with fast training and conformal uncertainty quantification](/20260626-20260705/2606.29440v1-randomized-neural-operator-for-parametric-pdes-with-fast-training-and-conformal-uncertainty-quantification)  
   标签：评分：9.0/10、query:flow-pred
   evidence：用于参数PDE的随机化神经算子，训练速度快
2. [Temperature Field Reconstruction of Tungsten Monoblock Divertor on EAST using Physics-aware Neural Operator Transformer](/20260626-20260705/2606.31574v1-temperature-field-reconstruction-of-tungsten-monoblock-divertor-on-east-using-physics-aware-neural-operator-transformer)  
   标签：评分：9.0/10、query:flow-pred
   evidence：利用物理感知神经算子Transformer进行温度场重建
3. [SNAP-FM: Sparse Nonlinear Accelerated Projection for Physics-Constrained Generative Modeling](/20260626-20260705/2607.00095v1-snap-fm-sparse-nonlinear-accelerated-projection-for-physics-constrained-generative-modeling)  
   标签：评分：9.0/10、query:pc-latent
   evidence：物理约束生成建模与稀疏非线性投影
4. [From Spectral Methods to Sample Complexity Bounds for Fourier Neural Operators](/20260626-20260705/2607.00320v1-from-spectral-methods-to-sample-complexity-bounds-for-fourier-neural-operators)  
   标签：评分：9.0/10、query:flow-pred
   evidence：傅里叶神经算子在演化方程上的近似与学习保证，直接相关神经算子流体动力学
5. [GAIA: Geometry-Adaptive Operator Learning for Forward and Inverse Problems](/20260626-20260705/2607.01128v1-gaia-geometry-adaptive-operator-learning-for-forward-and-inverse-problems)  
   标签：评分：9.0/10、query:flow-pred
   evidence：任意几何上的神经算子用于PDE正向和逆问题
6. [Fourier Neural Operators with Least-Squares Readout Refit for Learning Random Obstacle-to-Solution Maps](/20260626-20260705/2606.29436v1-fourier-neural-operators-with-least-squares-readout-refit-for-learning-random-obstacle-to-solution-maps)  
   标签：评分：8.0/10、query:flow-pred
   evidence：傅里叶神经算子结合读出修正用于算子学习，可应用于流体动力学
7. [Bidirectional Autoregressive Latent Diffusion for Forward and Inverse Magnetohydrodynamics](/20260626-20260705/2606.29620v1-bidirectional-autoregressive-latent-diffusion-for-forward-and-inverse-magnetohydrodynamics)  
   标签：评分：8.0/10、query:flow-pred
   evidence：潜在扩散模型用于磁流体动力学流场正逆预测，支持稀疏诊断
8. [Gappy Reconstruction of Bubbly Flows by Guided Diffusion Models](/20260626-20260705/2606.29843v1-gappy-reconstruction-of-bubbly-flows-by-guided-diffusion-models)  
   标签：评分：8.0/10、query:flow-pred
   evidence：利用扩散模型从有限数据重构流场

### 速读区论文标签
1. [Disentangling Continuous-Time Latent Dynamics: Identifiability of Latent SDEs via Diffusion Shifts](/20260626-20260705/2606.28228v1-disentangling-continuous-time-latent-dynamics-identifiability-of-latent-sdes-via-diffusion-shifts)  
   标签：评分：8.0/10、query:pc-latent
   evidence：基于扩散偏移的连续时间潜动态可辨识性
2. [A Path-Space Formulation of Prediction in World Models: From a Single Action to Prediction, Planning, and Irreversibility](/20260626-20260705/2606.28751v1-a-path-space-formulation-of-prediction-in-world-models-from-a-single-action-to-prediction-planning-and-irreversibility)  
   标签：评分：8.0/10、query:pc-latent
   evidence：世界模型中潜在动力学的路径空间形式，用于预测与规划
3. [ScaleAware-JEPA: Latent Representation for Discovery in Multiscale Physical Fields](/20260626-20260705/2606.29723v1-scaleaware-jepa-latent-representation-for-discovery-in-multiscale-physical-fields)  
   标签：评分：8.0/10、query:pc-latent
   evidence：多尺度物理场的潜在坐标学习框架
4. [Offline accuracy is not enough: closed-loop instability and stabilisation of a wall-sensor neural estimator in opposition control](/20260626-20260705/2606.30484v1-offline-accuracy-is-not-enough-closed-loop-instability-and-stabilisation-of-a-wall-sensor-neural-estimator-in-opposition-control)  
   标签：评分：8.0/10、query:flow-pred
   evidence：利用循环神经网络估计器从稀疏壁面传感器重构流场
5. [A Multi-Resolution Finite-Volume Inspired Deep Learning Framework for Spatiotemporal Dynamics Prediction](/20260626-20260705/2607.00460v1-a-multi-resolution-finite-volume-inspired-deep-learning-framework-for-spatiotemporal-dynamics-prediction)  
   标签：评分：8.0/10、query:flow-pred
   evidence：物理信息深度学习框架用于时空动力学预测
6. [Effects of thermochemical modelling on a hypersonic shock-wave/turbulent boundary-layer interaction](/20260626-20260705/2606.28018v1-effects-of-thermochemical-modelling-on-a-hypersonic-shock-waveturbulent-boundary-layer-interaction)  
   标签：评分：7.0/10、query:sfc
   evidence：高超声速激波/湍流边界层相互作用的热化学建模
7. [A Trainable-by-Parts Operator Learning Framework: Bridging DeepONet and Karhunen-Loeve Expansions for Large-Scale Applications](/20260626-20260705/2606.28519v1-a-trainable-by-parts-operator-learning-framework-bridging-deeponet-and-karhunen-loeve-expansions-for-large-scale-applications)  
   标签：评分：7.0/10、query:flow-pred
   evidence：算子学习框架用于大规模PDE包括地下流
8. [Data-driven linear analysis of turbulent flows](/20260626-20260705/2606.28569v1-data-driven-linear-analysis-of-turbulent-flows)  
   标签：评分：7.0/10、query:flow-pred
   evidence：湍流数据驱动线性分析方法
9. [Weak Dominant Balance for Robust Identification of Dynamically Consistent Fluid Flow Structure](/20260626-20260705/2606.29047v1-weak-dominant-balance-for-robust-identification-of-dynamically-consistent-fluid-flow-structure)  
   标签：评分：7.0/10、query:flow-pred
   evidence：无导数流体流动结构识别
10. [Kriging and neural network models for pressure losses across perforated plates](/20260626-20260705/2606.29628v1-kriging-and-neural-network-models-for-pressure-losses-across-perforated-plates)  
   标签：评分：6.0/10、query:flow-pred
   evidence：数据驱动的湍流压降预测模型
11. [I-BBS: Coordinate-Free Inference of Latent Sub-Manifolds Using Random Distance Matrix Theory](/20260626-20260705/2606.29675v1-i-bbs-coordinate-free-inference-of-latent-sub-manifolds-using-random-distance-matrix-theory)  
   标签：评分：6.0/10、query:pc-latent
   evidence：从距离矩阵推断潜在子流形
12. [Verified residual-specific explicit derivative kernels for physics-informed learning and discretized PDE adjoints](/20260626-20260705/2606.29702v1-verified-residual-specific-explicit-derivative-kernels-for-physics-informed-learning-and-discretized-pde-adjoints)  
   标签：评分：6.0/10、query:flow-pred
   evidence：用于物理信息学习和CFD伴随的显式导数核
13. [Efficient Wall-Modeled High-Order Compact Gas-Kinetic Scheme for Compressible Turbulent Flows](/20260626-20260705/2606.30061v1-efficient-wall-modeled-high-order-compact-gas-kinetic-scheme-for-compressible-turbulent-flows)  
   标签：评分：6.0/10、query:flow-pred
   evidence：用于可压缩湍流预测的壁模型气体动力学格式


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
