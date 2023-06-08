# 时间序列预测工具：TSF-SVR
TSF-SVR是由大连理工大学建设工程学部智能交通研究所的徐洪峰老师和樊莉莉、王铭臣两位同学合作开发的一款单变量时间序列预测工具，可以帮助本地计算机上未部署Python环境或者部署了Python环境但未安装Sklearn的用户轻松完成SVR单变量建模和预测任务，让用户不必为精通SVR基本原理和Python程序设计而花费时间。

TSF-SVR为用户提供了两项功能：
（1）加载一个按照时间顺序排列的样本数据集。将样本数据集分割成前后两部分，前部为训练集，用于确定SVR模型的参数取值；后部为测试集，用于评价SVR模型的预测精度；
（2）采用MSE、RMSE、MAE和MAPE评价SVR模型的预测精度，得到样本数据集外十个时间步的预测结果。TSF-SVR的输出结果被存储为Excel文件，如图1所示。
