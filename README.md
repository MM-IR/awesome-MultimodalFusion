# awesome-MultimodalFusion
多模态融合综述

# 张长青老师报告
## 1.多模态融合研究背景@比如智慧医疗与计算机视觉

![](SmartInsur.png)

这里就是计算机视觉存在的图片的几种传感器～

![](Multiview.png)

### 多模态融合的主要目标：
利用多源信息有效发现潜在模式，利用好模态之间的互补性～

重点：

![](Multiviewst.png)

一致性一般被称作common/sharing。
互补性就是会被称为independent/mutual。
兼容性就是他们该如何混合呢？

## 常见的一致性策略
![](Common.png)
这个最常见的思路就是CCA（典型）

![](Common2.png)
第二种就是多模态数据高阶张量模型。
这个的核心思想就是我们不再从pair的角度上进行约束，而是从全局/整体的角度上进行约束。

![](Common3.png)
这里就是讲解了多模态数据高阶张量模型～

## 常见的互补性
![](Complement.png)

表示学习就是多模态共享信息进行保留，特有信息进行分离。

![](Complement2.png)
这里就是有显著增强多样性的策略哦～

互补性就是尽量让其独立！（希尔伯特独立性标准）

## 然后就是最终的兼容性策略
![](JR.png)

## 多模态数据完备表示@兼容性的挑战
![](JRAll.png)

我们在不知道先验的情况下更希望保持多视角数据存在的本身的关联～
两者之间@共享信息以及独立的需要权衡保留。
![](JRAll2.png)
