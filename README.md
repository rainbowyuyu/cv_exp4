# cv_exp4
采用不分文件，仅使用单个jupyter完成实验

# 对于老师的代码做了一下修正和改进
1、修正了大小写以及一些中文标点符号
2、由于mnist是gz的数据集，更改load_labels和load_images函数，加入gzip
3、Qt优化防重复初始化进程
4、文件检测，防止重复训练模型耗时
