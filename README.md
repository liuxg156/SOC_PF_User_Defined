# SOC_PF_User_Defined
基于PF原理，在simulink中搭建用于电池SOC计算的EKF模块,导出为Matlab2017a版本
以simulink基本模块搭建PF算法，用于计算电池SOC；
电池为NCM电池，标称容量为2.9Ah，测试工况为UDDS工况，由于数据为电池初期数据，实际可用容量为3.1Ah左右；
电池模型为二阶RC模型；
电池模型参数采用的式AFFRLS算法辨识后取平均值；
真值采用Ah积分法配合真实容量计算。
