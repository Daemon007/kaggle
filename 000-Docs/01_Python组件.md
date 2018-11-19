
# Python组件

Python常用组件介绍: 简介、功能、使用

## NumPy

NumPy(Numerical Python) 是 Python 语言的一个扩展程序库，支持大量的维度数组与矩阵运算，此外也针对数组运算提供大量的数学函数库。

NumPy 是一个运行速度非常快的数学库，主要用于数组计算，包含：

* 一个强大的N维数组对象 ndarray
* 广播功能函数
* 整合 C/C++/Fortran 代码的工具
* 线性代数、傅里叶变换、随机数生成等功能


### NumPy 应用

NumPy 通常与 SciPy（Scientific Python）和 Matplotlib（绘图库）一起使用， 这种组合广泛用于替代 MatLab，是一个强大的科学计算环境，有助于我们通过 Python 学习数据科学或者机器学习。

SciPy 是一个开源的 Python 算法库和数学工具包。

SciPy 包含的模块有最优化、线性代数、积分、插值、特殊函数、快速傅里叶变换、信号处理和图像处理、常微分方程求解和其他科学与工程中常用的计算。

Matplotlib 是 Python 编程语言及其数值数学扩展包 NumPy 的可视化操作界面。它为利用通用的图形用户界面工具包，如 Tkinter, wxPython, Qt 或 GTK+ 向应用程序嵌入式绘图提供了应用程序接口（API）。


## Pandas

### Pandas库的介绍

Pandas是一个开放源码的基于NumPy的Python库，它使用强大的数据结构提供高性能的数据操作和分析工具。它的名字：Pandas是从Panel Data - 多维数据的计量经济学(an Econometrics from Multidimensional data)。

2008年，为满足需要高性能，灵活的数据分析工具，开发商Wes McKinney开始开发Pandas。

在Pandas之前，Python主要用于数据迁移和准备。它对数据分析的贡献更小。 Pandas解决了这个问题。 使用Pandas可以完成数据处理和分析的五个典型步骤，而不管数据的来源 - 加载，准备，操作，模型和分析。

Python Pandas用于广泛的领域，包括金融，经济，统计，分析等学术和商业领域。

### **Pandas的主要特点**

* 快速高效的DataFrame对象，具有默认和自定义的索引。
* 将数据从不同文件格式加载到内存中的数据对象的工具。
* 丢失数据的数据对齐和综合处理。重组和摆动日期集。
* 基于标签的切片，索引和大数据集的子集。
* 可以删除或插入来自数据结构的列。
* 按数据分组进行聚合和转换。
* 高性能合并和数据加入。
* 时间序列功能。

## Matlpotlib

Matplotlib 是一个 Python 的 2D绘图库，它以各种硬拷贝格式和跨平台的交互式环境生成出版质量级别的图形。

通过 Matplotlib，开发者可以仅需要几行代码，便可以生成绘图，直方图，功率谱，条形图，错误图，散点图等。

## Seaborn

seaborn同matplotlib一样，也是Python进行数据可视化分析的重要第三方包。但seaborn是在 matplotlib的基础上进行了更高级的API封装，使得作图更加容易，图形更加漂亮。

实际上并不认为seaborn可以替代matplotlib。虽然seaborn可以满足大部分情况下的数据分析需求，但是针对一些特殊情况，还是需要用到matplotlib的。换句话说，matplotlib更加灵活，可定制化，而seaborn像是更高级的封装，使用方便快捷。

应该把seaborn视为matplotlib的补充，而不是替代物。

### Seaborn学习内容

seaborn的学习内容主要包含以下几个部分：

**风格管理**

* 绘图风格设置
* 颜色风格设置

**绘图方法**

* 数据集的分布可视化
* 分类数据可视化
* 线性关系可视化

**结构网格**

* 数据识别网格绘图

## Plotly

lotly的Python图形库使互动的出版质量图表成为在线。 如何制作线图，散点图，面积图，条形图，误差线，箱形图，直方图，热图，子图，多轴，极坐标图和气泡图的示例。

其功能强大到不仅与多个主流绘图软件的对接，而且还可以像Excel那样实现交互式制图，而且图表种类齐全，并可以实现在线分享以及开源，等等；这种功能强大到还没有一个人能够完全掌握其全部应用，甚至国内对它的介绍使用也仅仅只是其中一部分。

## 相关链接

* NumPy 官网 http://www.numpy.org/
* NumPy 源代码：https://github.com/numpy/numpy
* NumPy 教程: http://www.runoob.com/numpy/numpy-tutorial.html

* Pandas 官网: http://pandas.pydata.org/
* Pandas 教程: https://www.yiibai.com/pandas/python_pandas_quick_start.html

* SciPy 官网：https://www.scipy.org/
* SciPy 源代码：https://github.com/scipy/scipy

* Matplotlib 官网：https://matplotlib.org/
* Matplotlib 源代码：https://github.com/matplotlib/matplotlib
