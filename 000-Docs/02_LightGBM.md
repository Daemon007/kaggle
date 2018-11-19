# LightGBM

## 介绍

xgboost的出现，让数据民工们告别了传统的机器学习算法们：RF、GBM、SVM、LASSO 等。现在微软推出了一个新的boosting框架，想要挑战xgboost的江湖地位。

顾名思义，lightGBM包含两个关键点：light即轻量级，GBM 梯度提升机。

LightGBM 是一个梯度 boosting 框架，使用基于学习算法的决策树。它可以说是分布式的，高效的，有以下优势：

* 更快的训练效率
* 低内存使用
* 更高的准确率
* 支持并行化学习
* 可处理大规模数据

与常用的机器学习算法进行比较：速度飞起

![LightGBM速度比较](pic/20170802163943148.jpeg)


## 安装

### OSX

LightGBM 依赖于 OpenMP 进行编译, 然而 Apple Clang 不支持它.

请使用以下命令来安装 gcc/g++ :

```shell
brew install cmake
brew install gcc --without-multilib
```

然后安装 LightGBM:

``` shell
git clone --recursive https://github.com/Microsoft/LightGBM ; cd LightGBM
export CXX=g++-8 CC=gcc-8
mkdir build ; cd build
cmake ..
make -j4
```



## 链接

* LightGBM 中文文档: http://lightgbm.apachecn.org/cn/latest/