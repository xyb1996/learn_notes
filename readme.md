# 第一章数学基础

## 概率论
<img src = '/imgs/常见函数分布.jpg'{width=750px}>
	
### 极大似然估计
极大似然估计提供了一种给定观察数据来评估模型参数的方法，通过观察若干实验结果，得到某组能使样本出现的最大概率的参数值。

# 第二章推荐系统介绍

## 推荐系统的主要元素
物品集合、用户、场景、推荐引擎、推荐结果集。

## 推荐引擎重要模块
* 召回模块：通过多种召回方法进行组合召回，挑选用户最可能感兴趣的物品，比如：用户最近点击物品召回相似物品，用户兴趣类目召回物品。
* 排序模块：针对召回模块对物品进行精排，常用特征有：标签特征、物品的特征以及组合特征。
* 后排模块：需要对排序列表进行调整，如运营干预、优先级调权、指定下发规则。

常见召回算法：
![](https://github.com/xyb1996/learn_notes/blob/master/imgs/常见召回模型.jpg{width=750px})

常见排序算法：
![](https://github.com/xyb1996/learn_notes/blob/master/imgs/3.jpg{width=750px})
![](https://github.com/xyb1996/learn_notes/blob/master/imgs/4.jpg{width=750px})

