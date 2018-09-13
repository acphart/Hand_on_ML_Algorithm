# Hand_on_ML_Algorithm
这里是我自己实现的一些机器学习的算法，主要是为了学习算法的原理，没有过多考虑性能 ~~
## 文件说明
- 这里的代码都是在Jupyter Notebook中运行，下载后直接在Jupyter Notebook中打开运行即可，因为对于自己动手实现算法，在Jupyter Notebook中进行交互式操作要方便快捷得多
## 1. LinearRegression_multi_polynomal
- 用线性回归实现多项式拟合，这样就可以实现简单的非线性拟合了，基于`LinearRegression_single_variabel`
## 2. LinearRegression_single_variabel
- 实现单变量线性回归算法的训练过程，最小二乘法
## 3. LogisticRegression_linear_classifier
- 实现两个特征变量的逻辑回归算法的线性分类器（二分类），交叉熵代价函数
## 4. ANN_StochasticGradientDescent
#### 4.1 参考文献
- Michael A. Nielsen, “Neural Networks and Deep Learning”, Determination Press, 2015.
#### 4.2 项目介绍
- 这里实现了一个可以学习mnist手写数字特征的人工神经网络类`ANN`。
- 此版本的`ANN`基于随机梯度下降算法实现，梯度由反向传播算法计算，神经元激活函数为`sigmoid()`，或称`logistic` 函数。
- 此项目主要为学习之用，在实现核心功能的前提下，尽量编写简单、易于阅读的代码，暂时没有考虑优化。
- 此项目所使用数据为Kaggle竞赛中Digit_Recognizer的train.csv文件，数据可在此处下载[Kaggle:Digit Recognizer](https://www.kaggle.com/c/digit-recognizer/data)
#### 4.3 下一步计划
- 进一步调参
- 加入正则化，尝试`L1`正则和`L2`正则
- 改变神经元激活函数，尝试双曲正切函数`tanh()`和修正线性单元`ReLU()`
- 搭建卷积神经网络，使得网络可以学习图像结构特征
