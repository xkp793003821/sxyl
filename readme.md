## 数学原理实验四次作业
# 1 线性回归
在这里利用Keras直接使用一个全连接层等价于线性回归

代码见：1.py
# 2 逻辑回归（二分类任务）
简单的使用Dense全连接层加上sigmoid激活函数，二分类任务。

代码见：2.py
# 3 多分类任务（softmax）
使用softmax作为为激活函数

代码见3_sk.py
# 4 高斯判别分析（GDA）
代码见4.py

# 数据预处理

见 dataprocess.py 文件内分别定义了三个函数用于三个文件的数据预处理，并且进一步利用sklearn的标准化以及onehot完成独热编码的生成