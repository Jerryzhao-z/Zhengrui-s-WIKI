# 和SVM有关的算法

July大大的SVM三重境界在我学习SVM算法之初给我解答了很多疑惑，对于初学者而言非常友好。链接在reference里，建议初学者多读两遍。这篇文章可以视为三境界的扩展，我个人水平有限，还望指正。

### SVM的直觉认知

SVM的英文全称是support vector machine。 直观上理解，这一算法的目标是找到一个可以把两类数据点分开的最优超平面hyperplane。 而support vectors指的是距离这一超平面最近的几个数据点，可以说正是这几个数据点定义了这一超平面。

![](/assets/svm.png)

### SVM的理论推导

### SVM的求值算法

### SVM的实际应用和推广

SVM的基本模型主要是用于分类问题，实际应用可以这样选取算法

```
if (线性可分)
    SVM
elif (近似线性可分)
    soft SVM -> C-SVM or mu-SVM
else
    # 线性不可分
    kernel SVM
```

此外，RVM可以通过一个先验控制控制参数的稀疏度。

而现实生活中大部分的问题往往并不是 supervised 问题，即数据并不是全部标注好的，此时，Transductive SVM可以帮助我们借助已有的数据逐步标注未知数据，最终获得hyperplane的参数。

#### 分类问题

##### C-SVM

##### mu-SVM

#### Transductive SVM

#### RVM & RVR

#### 聚类问题 SVC

#### 回归问题 SVR

### referenece:

[支持向量机通俗导论（理解SVM的三层境界）](http://blog.csdn.net/v_july_v/article/details/7624837)\(2017/7/10\)

