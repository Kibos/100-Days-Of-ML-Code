# 机器学习100天

英文原版请移步[Avik-Jain](https://github.com/Avik-Jain/100-Days-Of-ML-Code)。数据在[这里](https://github.com/MachineLearning100/100-Days-Of-ML-Code/tree/master/datasets)。

翻译前请先阅读[规范](Translation%20specification.MD)。常见问题解答见[FAQ](FAQ.MD)。

# 目录
- 有监督学习
  - [数据预处理](#数据预处理--第1天)
  - [简单线性回归](#简单线性回归--第2天)
  - [多元线性回归](#多元线性回归--第3天)
  - [逻辑回归](#逻辑回归--第4天)
  - [k近邻法(k-NN)](#k近邻法k-nn--第7天)
  - [支持向量机(SVM)](#支持向量机svm--第12天)
  - [决策树](#决策树--第23天)
  - [随机森林](#随机森林--第33天)
- 无监督学习
  - [K-均值聚类](#k-均值聚类--第43天)
  - [层次聚类](#层次聚类--第54天)

## 数据预处理 | 第1天
[数据预处理实现](https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Code/Day%201_Data_Preprocessing.md)

<p align="center">
  <img src="https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%201.jpg">
</p>

## 简单线性回归 | 第2天
[简单线性回归实现](https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Code/Day%202_Simple_Linear_Regression.md)

<p align="center">
  <img src="https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%202.jpg">
</p>

## 多元线性回归 | 第3天
[多元线性回归实现](https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Code/Day%203_Multiple_Linear_Regression.md)

<p align="center">
  <img src="https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%203.png">
</p>

## 逻辑回归 | 第4天
<p align="center">
  <img src="https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%204.jpg">
</p>

## 逻辑回归 | 第5天
今天我深入研究了逻辑回归到底是什么，以及它背后的数学是什么。学习了如何计算代价函数，以及如何使用梯度下降法来将代价函数降低到最小。<br>
由于时间关系，我将隔天发布信息图。如果有人在机器学习领域有一定经验，并愿意帮我编写代码文档，也了解github的Markdown语法，请在领英联系我。

## 逻辑回归 | 第6天
[逻辑回归实现](https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Code/Day%206_Logistic_Regression.md)

## K近邻法(k-NN) | 第7天
<p align="center">
  <img src="https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%207.jpg">
</p>

## 逻辑回归背后的数学 | 第8天
为了使我对逻辑回归的见解更加清晰，我在网上搜索了一些资源或文章，然后我就发现了Saishruthi Swaminathan的<a href = "https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc">这篇文章</a><br>

它给出了逻辑回归的详细描述。请务必看一看。

## 支持向量机(SVM) | 第9天
直观了解SVM是什么以及如何使用它来解决分类问题。

## 支持向量机和K近邻法 | 第10天
了解更多关于SVM如何工作和实现knn算法的知识。

## K近邻法(k-NN) | 第11天
[K近邻法(k-NN)实现](https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Code/Day%2011_K-NN.md)

## 支持向量机(SVM) | 第12天
<p align="center">
  <img src="https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%2012.jpg">
</p>

## 支持向量机(SVM) | 第13天
[SVM实现](https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Code/Day%2013_SVM.md)

## 支持向量机(SVM)的实现 | 第14天
今天我在线性相关数据上实现了SVM。使用Scikit-Learn库。在scikit-learn中我们有SVC分类器，我们用它来完成这个任务。将在下一次实现时使用kernel-trick。Python代码见[此处](https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Code/Day%2013_SVM.py),Jupyter notebook见[此处](https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Code/Day%2013_SVM.ipynb)。

## 朴素贝叶斯分类器(Naive Bayes Classifier)和黑盒机器学习(Black Box Machine Learning) | 第15天
学习不同类型的朴素贝叶斯分类器同时开始<a href="https://bloomberg.github.io/foml/#home">Bloomberg</a>的课程。课程列表中的第一个是黑河机器学习。它给出了预测函数，特征提取，学习算法，性能评估，交叉验证，样本偏差，非平稳性，过度拟合和超参数调整的整体观点。

## 通过内核技巧实现支持向量机 | 第16天
使用Scikit-Learn库实现了SVM算法以及内核函数，该函数将我们的数据点映射到更高维度以找到最佳超平面。

## 在Coursera开始深度学习的专业课程 | 第17天
在1天内完成第1周和第2周内容以及学习课程中的逻辑回归神经网络。

## 继续Coursera上的深度学习专业课程 | 第18天
完成课程1。用Python自己实现一个神经网络。

## 学习问题和Yaser Abu-Mostafa教授 | 第19天
开始Yaser Abu-Mostafa教授的Caltech机器学习课程-CS156中的课程1。这基本上是对即将到来的课程的一种介绍。他也介绍了感知算法。

## 深度学习专业课程2 | 第20天
完成改进深度神经网络第1周内容：参数调整，正则化和优化。

## 网页搜罗 | 第21天
观看了一些关于如何使用Beautiful Soup进行网络爬虫的教程，以便收集用于构建模型的数据。

## 学习还可行吗? | 第22天
完成Yaser Abu-Mostafa教授的Caltech机器学习课程-CS156中的课程2。学习Hoeffding不等式。

## 决策树 | 第23天
<p align="center">
  <img src="https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%2023%20-%20Chinese.jpg">
</p>

## 统计学习理论的介绍 | 第24天
Bloomberg ML课程的第3课介绍了一些核心概念，如输入空间，动作空间，结果空间，预测函数，损失函数和假设空间。

## 决策树 | 第25天
[决策树实现](https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Code/Day%2025_Decision_Tree.md)

## 跳到复习线性代数 | 第26天
发现YouTube一个神奇的频道[3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw)，它有一个播放列表《线性代数的本质》。看完了4个视频，包括了向量，线性组合，跨度，基向量，线性变换和矩阵乘法。

B站播放列表在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=9450)。

## 跳到复习线性代数 | 第27天
继续观看了4个视频，内容包括三维变换、行列式、逆矩阵、列空间、零空间和非方矩阵。

B站播放列表在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=9450)。

## 跳到复习线性代数 | 第28天
继续观看了3个视频，内容包括点积和叉积。

B站播放列表在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=9450)。

## 跳到复习线性代数 | 第29天
观看了剩余的视频12到14，内容包括特征向量和特征值，以及抽象向量空间。

B站播放列表在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=9450)。

## 微积分的本质 | 第30天
完成上一播放列表后，YouTube推荐了新内容《微积分的本质》，今天看完了其中的3个视频，包括导数、链式法则、乘积法则和指数导数。

B站播放列表在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=9450)。

## 微积分的本质 | 第31天
观看了2个视频，内容包括隐分化与极限。

B站播放列表在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=13407)。

## 微积分的本质 | 第32天
观看了剩余的4个视频，内容包括积分与高阶导数。

B站播放列表在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=13407)。

## 随机森林 | 第33天
<p align="center">
  <img src="https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%2033.png">
</p>

## 随机森林 | 第34天
[随机森林实现](https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Code/Day%2034_Random_Forests.md)

## 什么是神经网络？ | 深度学习，第1章 | 第 35天
Youtube频道3Blue1Brown中有精彩的视频介绍神经网络。这个视频提供了很好的解释，并使用手写数字数据集演示基本概念。

B站视频在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=26587)。

## 梯度下降法，神经网络如何学习 | 深度学习，第2章 | 第36天
Youtube频道3Blue1Brown关于神经网络的第2部分，这个视频用有趣的方式解释了梯度下降法。推荐必须观看169.

B站视频在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=26587)。

## 反向传播法究竟做什么？ | 深度学习，第3章 | 第37天
Youtube频道3Blue1Brown关于神经网络的第3部分，这个视频主要介绍了偏导数和反向传播法。

B站视频在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=26587)。

## 反向传播法演算 | 深度学习，第4章 | 第38天
Youtube频道3Blue1Brown关于神经网络的第3部分，这个视频主要介绍了偏导数和反向传播法。

B站视频在[这里](https://space.bilibili.com/88461692/#/channel/detail?cid=26587)。

## 第1部分 | 深度学习基础Python，TensorFlow和Keras | 第39天
视频地址在[这里](https://www.youtube.com/watch?v=wQ8BIBpya2k&t=19s&index=2&list=PLQVvvaa0QuDfhTox0AjmQ6tvTgMBZBEXN)。

## 第2部分 | 深度学习基础Python，TensorFlow和Keras | 第40天
视频地址在[这里](https://www.youtube.com/watch?v=wQ8BIBpya2k&t=19s&index=2&list=PLQVvvaa0QuDfhTox0AjmQ6tvTgMBZBEXN)。

## 第3部分 | 深度学习基础Python，TensorFlow和Keras | 第41天
视频地址在[这里](https://www.youtube.com/watch?v=wQ8BIBpya2k&t=19s&index=2&list=PLQVvvaa0QuDfhTox0AjmQ6tvTgMBZBEXN)。

## 第4部分 | 深度学习基础Python，TensorFlow和Keras | 第42天
视频地址在[这里](https://www.youtube.com/watch?v=wQ8BIBpya2k&t=19s&index=2&list=PLQVvvaa0QuDfhTox0AjmQ6tvTgMBZBEXN)。

## K-均值聚类 | 第43天
转到无监督学习，并研究了聚类。可在[作者网站](http://www.avikjain.me/)查询。发现一个奇妙的[动画](http://shabal.in/visuals/kmeans/6.html)有助于理解K-均值聚类。
<p align="center">
  <img src="https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%2043.jpg">
</p>

## 层次聚类 | 第54天
<p align="center">
  <img src="https://github.com/MachineLearning100/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%2054.jpg">
</p>
