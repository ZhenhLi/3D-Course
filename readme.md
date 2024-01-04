## 1.公开课CSC2547

* https://www.pair.toronto.edu/csc2547-w21/schedule/
* 本课程介绍三维视觉的深度学习方法与现代进展。本文将在目标和场景层面上研究三维视觉任务的表示、学习方法与生成模型。而后将研究集合深度学习与深度学习相关的流形学习概念。本主题的3D特性在图形学、机器人学、内容创建、混合现实、生物特征识别等方面有很多潜在的应用。

### 目录结构
* 0. 课程介绍+3D表征介绍
* 1. 现代机器学习中的3D数据表征
  * PointNet & PointNet++
  * 3D形状的局部深度隐函数
  * 可选, Point2Surf, NOCS, DeepSDF
* 2. 学习：3D形状建模
  * PointConv
  * 用于点云学习的动态图CNN
  * KPConv
  * DeepSDF
  * 可选, PCT(Point Cloud Transformer), Learning Deformable Tetrahedral Meshes for 3D Reconstruction, PIE-NET
* 3. 3D数据处理的计算效率+场景理解
  * 客座演讲: Dr. Chris Choy， Nvidia，提出了MinowskiNets
  * 用于3D语义分割演示的虚拟多视图融合
  * 3D-SIS: RGBD扫描演示的3D语义实例分割
  * 可选, 使用Flow Capsules的无监督部分表示, OccuSeg, SparseConvNet
* 4. 3D生成建模
  * 三维结构生成模型的学习
  * PolyGen
  * 学习梯度场的形状生成
  * ShapeAssembly, 形状装配
  * 可选，StructureNet
* 5. 可区分渲染
  * 可区分渲染, 综述
  * 基于边缘采样的蒙特卡洛光线追踪
  * 具有隐式照明与材料呈现的多视角神经表面重建
  * 可微体积渲染
  * 可选, Soft Rasterizer: 用于基于图像的3D推理的可微渲染器, 学习使用基于插值的可微渲染器预测3D对象
* 6. 神经渲染NeRF
  * 神经体积渲染: NeRF及其他
  * 野外中的NeRF: 使用无约束图像集合的神经辐射场
  * 场景表示网络: 连续3D结构感知神经场景表示
  * 用于外观采集的神经反射场
* 7. NeRF应用
  * NSVF: 神经稀疏体素场
  * NeRFies: 变形体素神经辐射场
  * iNeRF: 用于姿态估计演示的逆神经辐射场
  * 可选, NASA, 神经关节形状近似; GRF: 学习一个通用的3D场景表示和渲染光场;
* 8. 等变与不变
  * 等距变换不变与等变图卷积网络
  * 规范等变网格CNN表示
  * 对称元素表示
  * 基于旋转等变特征表示的曲面有线神经网络
  * 神经网格流: 基于微分流的三维流形网格生成
* 9. 无监督3D学习
  * 野外图像中的可能对称变形3D目标无监督学习
  * 规范胶囊: 无监督胶囊在笛卡尔姿态呈现
  * 点对比PointContrast, 三维点云理解的无监督预训练
  * 学习Delaunay曲面元素用于网格重建
  * 可选: KeypointNet:通过端对端几何推理法线潜在的3D关键点; 用于3D人体姿态估计的无监督几何感知表示学习; 用流胶囊实现的无监督部件表示; 通过野外多视图图像实现的弱监督3D人体姿态学习；
* 10. 超越计算机视觉的几何深度学习
  * 客座, Prof. Jonathan Kelly，自监督深度姿态校正的鲁棒视觉里程计
  * 等距变换不变与等变图卷积神经网络
  * 基于RGB图像的6D目标检测隐式三维方向学习
  * NeMo: 鲁棒三维姿态估计
  * 可选, 6DoF GraspNet: 用于目标操作的抓取生成, 稠密融合: 通过迭代稠密融合的6D对象姿态估计，密集对象网格, 用于类别级机器人操作的关键点提供
* 11.  机器人中的3D视觉
  * 快速端到端的蛋白质表面光
  * 关系归纳偏差, 深度学习和图形网格演示
  * LanczosNet, 多尺度深度卷积网格演示
  * SIREN: 隐式神经表征与周期性激活函数
  * 可选, RigNet: 关节性字符的神经操纵, 3DGV研讨会 Michael Bronstein- 几何深度学习


## 2.鲁鹏-北邮-计算机视觉之三维重建

### 目录

* 1. 摄像机几何
* 2. 摄像机标定
* 3. 单视图几何
* 4. 三维重建基础及极几何
* 5. 双目立体视觉
* 6. 多视图几何
* 7. 运动恢复结构系统解析
* 8. SLAM系统解析
* 9. SLAM系统解析
* 10. 总结篇

## 3.深蓝学院 三维点云处理课程

* 全面讲解三维点云经典算法与深度学习前言算法；
* 手写经典的点云处理算法，不依赖PCL等第三方库

### 课程目录

* 准备
  * 开课仪式
  * 获取免费的GPU服务器资源
  * 点云作业要求
* part1 introduction and basic algorithms，简单介绍了点云数据的特性，从数据特性出发，讲解了PCA算法在点云处理中的算法原理与实际应用，还介绍了其他演变算法。
  * 三维点云介绍
  * 本章知识点的实际应用
  * PCA与Kernel PCA
  * 表面法向量与滤波器
  * ModelNet40
  * 作业题1
* part2 最近邻问题，从最基础的二叉树结构开始讲解，讲述了最近邻算法的基础框架，之后扩展到KDtree和Octree.
  * 二叉搜索树
  * KD-Tree
  * OCtree
  * 作业
* part3 聚类, 系统讲解了各种经典点云聚类算法，从基础公式推导讲起，详细讲述了各种点云聚类算法的实现思路和详细流程。
  * 数学要求
  * k-means
  * GMM
  * EM
  * spactral clustering
  * 作业3
* part4 模型拟合，讲解了一些适用性更广泛的聚类算法，如谱聚类、均值漂移以及DBSCAN，之后由点云聚类思想引出模型拟合的概念，探讨了经典的Hough变换以及RANSAC算法理念，将RANSAC理念用在地平面分割上。
  * spectral clustering
  * mean shift & dbscan
  * least_square
  * hough_transform
  * ransac
  * 作业4
* part5 点云深度学习
  * PointNet
  * PointNet++
  * DGCNN
  * GCN
  * 作业5
* part6 3D目标检测
  * 基于图像的目标检测
  * VoxelNet & PointPillar
  * PointRCNN
  * fusion
  * 作业6
* part7 3d特征检测
  * 引言与harris 2d
  * harris 3d & 6d
  * intrinsic shape signatures(ISS)
  * Deep learning 3D features - USIP
  * SO-Net
  * 作业7
* part8 3D特征描述
  * 经典方法PFH & FPFH
  * 经典方法SHOT
  * 3DMatch & Perfect Match
  * PPFNet & PPF-FoldNet
  * 作业8
* part9 配准
  * ICP
  * NDT
  * RANSAC配准
  * 作业9
* part10
  * 大作业

## 4. cs468-spring2017-MachingLearningfor3DData

* https://graphics.stanford.edu/courses/cs468-17-spring/schedule.html

### 课程目录
* 引言；
* 几何基础；
* 机器学习与几何模型介绍
* 形状描述子
* 刚体形状配准
* 形状分割与标记
* 形状相似性与检索，非刚性配准
* 共同配准，功能地图
* 形状建模
* 形状重建与合成
* 深度学习介绍
* 多视角数据Deepnet
* 体积数据Deepnet
* 点云数据Deepnet
* 场景分析
* 图CNN Deepnet
* 点云表征的3D深度学习
* 形状分析的持久同调?
* 基于点云分析和联合嵌入的三维深度学习
