# 机器学习算法

所谓机器学习，指的是可以通过一定程度的训练，获得一个在一定范围内具有很强泛化效果的模型。

这也就涉及到模型训练方法和对泛化效果的衡量方法。由此可以把机器学习算法根以下category分类

### 算法分类

机器学习算法上大致可以分为监督学习supervised learning, 非监督学习 unsupervised learning和强化学习 reinforcement learning.

reinforcement learning特点是通过反馈学习一个最优策略。让agent从环境中根据当前状态做出反应，以获得最大回报。

而supervised learning和unsupervised learning则无关反馈。supervised learning旨在给定输入和输出数据中，探索一个映射函数函数。而unsupervised learning则只有输入数据，没有输出数据，我们通过unsupervised learning去了解数据结构，发现数据本身的一些特征。

### ![](http://wx2.sinaimg.cn/large/63918611ly1fl012sbprvj21kw0zgn9e.jpg)监督学习

监督学习可以根据映射函数的输出是离散还是连续分为分类问题和回归问题。

### 非监督学习

非监督学习分为聚类问题和降维问题。某种程度上讲，聚类问题也可以视为一种降维的方法。

### 特征工程

巧妇难为无米之炊，数据是关键。而在大多数现实问题中，原始数据往往十分简洁，类似文字/图像/信号，特征工程就是基于这些基本数据找到哪些关键的特征作为模型的输入。

神经网络本身最大的优势就在于可以省去特征工程这一机器学习中的冗长而关键的步骤。神经网络隐层就是原始数据经过神经网络后得到的特征。

