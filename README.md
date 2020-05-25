# svm-smo algorithm (an example in the course CS229)
* *svm_shi.py* <br>
该文件中实现了一个简单的SVM，使用SMO进行优化，在选择优化的变量时采用随机选择的方式。
* *plattSMO.py* <br>
该文件也是采用SMO进行优化，在选择优化变量时，选择误差步长最大的两个变量进行优化，可以大幅提高优化速度。
该文件中还加入了核函数（线性核函数，RBF核函数）

- 参考链接
    - 原项目地址：https://github.com/huxinliang8888/svm
    - 坐标上升算法介绍： https://cloud.tencent.com/developer/article/1066666
    - SMO算法介绍：https://zhuanlan.zhihu.com/p/29212107
