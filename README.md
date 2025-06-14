# AI System Tutorial

## 写在前面
- 以下文章是我的在工作之余的总结，涉及AI算法到芯片等跨度宽泛的领域，我把这一系列的文章暂时称为AI System
- 我期望文章的风格尽可能简明扼要，这样从文字中可以一眼看到重点，但是会缺少些趣味
- 为了尽可能增加文章的连续可读性，我会穿插一些提问和解答，期望带来更多的思考
- 早期文章可读性较弱，但也作保留，同时，全部内容均已脱敏，不涉及本人曾经、当前公司的敏感信息
- 部分文章可能由于正在完善或其他原因暂时无法打开，follow me

## Keyword
- Linux 嵌入式 OpenCV C/C++ MachineLearning机器学习 SLAM Python CUDA Nvidia Jetson

### AI系统
- [一文讲完C++\操作系统核心基础](https://editor.csdn.net/md/?articleId=143722397)
- [一文讲完多线程多进程计算](https://editor.csdn.net/md/?articleId=126957040)
- [内存大小和地址对齐以及异构平台处理手段](https://editor.csdn.net/md/?articleId=128717886)
- [一文讲完NPU计算与调度机制](https://editor.csdn.net/md/?articleId=142140478)
- [一文讲完CPU计算与调度机制](https://editor.csdn.net/md/?articleId=142493629)
- [一文讲完GPU计算和调度机制](https://editor.csdn.net/md/?articleId=142522695)
- [一文讲完模型压缩、转换、量化和优化（CNN/Transformer）](https://editor.csdn.net/md/?articleId=143311499)
- [一文讲完AI框架和AI编译器及其优化](https://editor.csdn.net/md/?articleId=143430375)
- [一文讲完Transformer\LLM大模型优化及其训练部署](https://editor.csdn.net/md/?articleId=143722561)
- [一文讲完经典的网络模型设计](https://editor.csdn.net/md/?articleId=144293470)
- [如何自定义一个优化加速算子](https://editor.csdn.net/md/?articleId=144771948)
- [CNN\LLM模型量化全解-以TensorRT为例](https://editor.csdn.net/md/?articleId=147847420)

### 高性能计算/CUDA
- [CUDA编程之环境配置与小试牛刀（教程与代码-1）](https://editor.csdn.net/md/?articleId=123099324)
- [CUDA编程之线程存储与原子操作（教程与代码-2）](https://editor.csdn.net/md/?articleId=123130714)
- [CUDA编程之性能测试与流的概念（教程与代码-3）](https://editor.csdn.net/md/?articleId=123284853)
- [CUDA编程之OpenCV的应用（教程与代码-4）](https://editor.csdn.net/md/?articleId=123310371)
- [英特尔oneAPI—英特尔异构统一编程接口初识及其深度学习应用](https://editor.csdn.net/md/?articleId=124575650)
- [NCNN源码解析笔记](https://editor.csdn.net/md/?articleId=127059541)
- [TVM使用TE手动优化矩阵乘法算法解析与代码解读](https://editor.csdn.net/md/?articleId=129244956)
- [Linux系统CPU性能分析工具教程](https://editor.csdn.net/md/?articleId=133804896)
- [Linux程序调试工具使用教程-GDB\Coredump\多线程调试\ASAN](https://editor.csdn.net/md/?articleId=133806161)
- [卷积计算的特殊加速优化-im2col/Winograd/FFT](https://editor.csdn.net/md/?articleId=145380782)
- [GPU核心编程不完全指北-CUDA\TensorRT\Cudnn\Nsight](https://editor.csdn.net/md/?articleId=144350573)
- [矩阵转置的计算优化加速-CUDA\缓存\分块\SIMD](https://editor.csdn.net/md/?articleId=144542560)
- [矩阵乘法\卷积的NPU计算优化加速-分块\缓存\多核\异步\多BATCH](https://editor.csdn.net/md/?articleId=144890816)
- [矩阵乘法\卷积的CUDA计算优化加速-多维卷积\共享内存\分块\向量化](https://editor.csdn.net/md/?articleId=145243705)
- [Reduce\SoftMax算子的CUDA计算优化加速-分块\多流\共享内存\线程展开](https://editor.csdn.net/md/?articleId=145472361)
- [Sort排序的CUDA计算优化加速-冒泡\并归\双调](https://editor.csdn.net/md/?articleId=145472481)
- [最大池化的CUDA计算优化加速-CPU/CUDA实现](https://editor.csdn.net/md/?articleId=146539332)

### Jetson
- [一、初识Jetson Orin Nano Super 老黄带给我们惊喜了？](https://editor.csdn.net/md/?articleId=147595413)
- [二、TensorRT-LLM框架的性能优化](https://editor.csdn.net/md/?articleId=147961497)

### 机器学习
- [基于Scikit-Learn的典型例子-鸢尾花分类](https://editor.csdn.net/md/?articleId=102632784)
- [监督学习算法-二分类\多分类\回归\K邻近\威斯康辛乳腺癌\波士顿房价](https://editor.csdn.net/md/?articleId=102711180)
- [监督学习算法-决策树\决策树集成\核支持向量机](https://editor.csdn.net/md/?articleId=102865927)
- [带你实现课程设计-基于python的简易动物识别算法/知识工程](https://editor.csdn.net/md/?articleId=102939319)
- [监督学习算法-神经网络与不确定度](https://editor.csdn.net/md/?articleId=102944054)
- [无监督学习与预处理-预处理与缩放\主成分分析](https://editor.csdn.net/md/?articleId=103169318)
- [非矩阵分解与流行学习](https://editor.csdn.net/md/?articleId=103326846)
- [聚类算法的对比与评估-K均值\凝聚\密度空间聚类](https://editor.csdn.net/md/?articleId=103639759)
- [要求每个batch为相同的size](https://editor.csdn.net/md/?articleId=116233679)
- [无监督图像分类技术](https://editor.csdn.net/md/?articleId=117228554)
- [特征匹配+Homography找目标](https://editor.csdn.net/md/?articleId=118423919)
- [图像基础与神经网络及其应用](https://editor.csdn.net/md/?articleId=124575293)
- [硬件感知的神经网络自动搜索NAS研究综述](https://editor.csdn.net/md/?articleId=133852582)
- [多卡训练/混合精度/分布式训练之踩坑指北](https://editor.csdn.net/md/?articleId=122042975)

### SLAM
- [视觉里程计的入门实践](https://editor.csdn.net/md/?articleId=106357205)
- [对极几何学习与实践](https://editor.csdn.net/md/?articleId=106357146)
- [三角测量与PNP](https://editor.csdn.net/md/?articleId=106356148)
- [G2OBA优化及ICP的学习实践](https://editor.csdn.net/md/?articleId=106356092)
- [特征匹配的光流实践](https://editor.csdn.net/md/?articleId=106356072)
- [直接法应用](https://editor.csdn.net/md/?articleId=106356041)
- [状态估计系统和卡尔曼滤波](https://editor.csdn.net/md/?articleId=106356034)
- [BA和图优化的入门与实践](https://editor.csdn.net/md/?articleId=106356000)
- [滑动窗口法及其优化求解实践](https://editor.csdn.net/md/?articleId=106355973)
- [位姿图优化的入门与实践](https://editor.csdn.net/md/?articleId=106355948)
- [创建字典进行回环检测教程](https://editor.csdn.net/md/?articleId=106355895)
- [使用单目相机进行地图构建](https://editor.csdn.net/md/?articleId=106355881)
- [稠密建图的讨论与八叉树三维地图的构建](https://editor.csdn.net/md/?articleId=106355843)
- [视觉SLAM系统设计与未来研究探讨](https://editor.csdn.net/md/?articleId=106355800)

### Linux&嵌入式
- [gcov/lcov/gcovr代码覆盖率交叉编译使用解析](https://editor.csdn.net/md/?articleId=128935553)
- [基于arm的ubuntu系统该源为国内源/404的解决（rk3399/friendlydesktop/中科大）](https://blog.csdn.net/heroybc/article/details/100588547)
- [在ubuntu下make luvcview时出现fatalerror；SDL.h:No such file or directory的问题解决](https://blog.csdn.net/heroybc/article/details/100186083)
- [通讯模块SIM调试常见问题和解决-信号连接/指令发送](https://blog.csdn.net/heroybc/article/details/90108113)
- [安装MDK时遇到SVDConv exied with an error.No uVision SystemViewer file created](https://blog.csdn.net/heroybc/article/details/89298784)
- [Linux开发常见问题及解决方法-服务器连接相关问题](https://blog.csdn.net/heroybc/article/details/78562954)
- [Linux在nanopi m3的安装配置](https://blog.csdn.net/heroybc/article/details/78562379)
- [带你实现课程设计-51单片机最小系统以及蜂鸣器驱动电路](https://blog.csdn.net/heroybc/article/details/89216390)
- [带你实现课程设计-电子温湿度计/51单片机+1602+dht11显示温湿度](https://blog.csdn.net/heroybc/article/details/89377146)
- [Linux系统下OpenCV开发教程](https://blog.csdn.net/heroybc/article/details/78563534)
- [ubuntu报错Errors were encountered while processing: hostapd的解决](https://editor.csdn.net/md/?articleId=100643458)
- [解决ippicv下载问题，离线:ippicv_2019_lnx_intel64_general_20180723.tgz](https://editor.csdn.net/md/?articleId=101097166)
- [E: Release file for http://ports.ubuntu.comxxInRelease is not valid关于时间设置的问题解决](https://editor.csdn.net/md/?articleId=101227557)
- [VMWare虚拟机安装的系统找不到（超简单）](https://editor.csdn.net/md/?articleId=101367547)
- [Ubuntu系统生产力配置问题及解决方法-自动蓝牙连接/中文输入法](https://editor.csdn.net/md/?articleId=101831279)
- [Tensorflow2.0在windows安装简明教程（防坑）](https://editor.csdn.net/md/?articleId=102413424)
- [嵌入式开发常见问题及解决方法-找不到libgfortran.so.4/换国内源](https://editor.csdn.net/md/?articleId=102655764)
- [Deepin下的ROS安装与配置](https://editor.csdn.net/md/?articleId=104725467)
- [ROS机器人操作系统的安装使用和问题解决](https://editor.csdn.net/md/?articleId=106357251)
- [ubuntu18.04安装ROS避坑指南](https://editor.csdn.net/md/?articleId=106882084)

### C/C++/Python
- [cmake\makefile使用教程](https://editor.csdn.net/md/?articleId=124675483)
- [C语言核心概念总结](https://blog.csdn.net/heroybc/article/details/85626399)
- [常见排序算法与八皇后问题](https://editor.csdn.net/md/?articleId=103277969)
- [数据类型大小以及常见的ASCII码值](https://editor.csdn.net/md/?articleId=120989484)
- [带你实现课程设计-简单程序小游戏推箱子](https://blog.csdn.net/heroybc/article/details/86511390)
- [AI系统开发常用的Python脚本合集](https://editor.csdn.net/md/?articleId=117924952)
- [绘制常见激活函数代码\显示试验可视化对比进行拼接](https://editor.csdn.net/md/?articleId=121374393)

### Other
- [LabviewNI服务定位器未运行的解决办法](https://blog.csdn.net/heroybc/article/details/89286194)
- [看看校招技术面技术你需要做什么-控制工程专业典型校招岗位要求汇总](https://blog.csdn.net/heroybc/article/details/95636768)
- [编程之美系列1](https://editor.csdn.net/md/?articleId=107530868)
- [文献管理软件抓去中文文献引用](https://editor.csdn.net/md/?articleId=120777803)
- [光流常见数据集下载教程](https://editor.csdn.net/md/?articleId=121793608)
- [KITTI raw 数据集获取方法](https://editor.csdn.net/md/?articleId=123488047)

