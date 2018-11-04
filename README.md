# machine_learning
哈尔滨工业大学2018年秋季机器学习相关实验

## lab 1 多项式拟合正弦函数
- [x] 1. 生成数据，加入噪声；
- [x] 2. 用高阶多项式函数拟合曲线；
- [x] 3. 用解析解求解两种loss的最优解（无正则项和有正则项）
- [x] 4. 优化方法求解最优解（梯度下降，共轭梯度）；
- [x] 5. 用你得到的实验数据，解释过拟合。
- [x] 6. 用不同数据量，不同超参数，不同的多项式阶数，比较实验效果。
- [x] 7. 语言不限，可以用matlab，python。求解解析解时可以利用现成的矩阵求逆。梯度下降，共轭梯度要求自己求梯度，迭代优化自己写。不许用现成的平台，例如pytorch，tensorflow的自动微分工具。

## lab 2 Logistics Regression 逻辑回归
- [x] 1.实现两种损失函数的参数估计（1、无惩罚项；2、加入对参数的惩罚），可以采用梯度下降、共轭梯度或者牛顿法等。

- [x] 2. 可以手工生成两个分别类数据（可以用高斯分布），验证你的算法。考察类条件分布不满足朴素贝叶斯假设，会得到什么样的结果。
- [x] 3. 逻辑回归有广泛的用处，例如广告预测。可以到UCI的网站上，找一实际数据加以测试，共使用3种不同数据(Mushroom, Blood Donation 和Banknote)。

## lab 3 实现k-means聚类方法和混合高斯模型
### 实验目标
- [x] 实现一个k-means算法和混合高斯模型，并用EM算法估计模型中的参数。
### 测试
用高斯分布产生k个高斯分布的数据(不同均值和方差)(其中参数自己设定)
- [x] 用k-means聚类测试效果
- [x] 用混合高斯模型和你实现的EM算法估计参数，看看每次迭代后似然值变化情况，考察EM算法是否可以获得正确结果(与你的设定结果比较)。
### 应用
- [x] 可以在UCI上找一个简单数据，用你实现的GMM进行聚类。
<!-- 存在问题 在Iris数据上GMM表现一般 -->