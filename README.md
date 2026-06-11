# Nonlinear-Analysis
Analysis of Load Data from Data Centers and Wind Farms  

数据集：  
1. Kelmarsh 风机功率数据 WIND_CSV.csv (10 min 间隔, 2016-01-03 ~ 2017-01-01)  
2. 阿里 DLRM 算力任务调度 Trace JOB_CSV.csv和NODE_CSV.csv (instance 级时间戳, 秒)  
 
运行方法:  
1.pip install numpy、pandas、scipy、scikit-learn、torch、matplotlib、pywavelets、tqdmpython  
2.code.py（可以在pycharm环境中运行，如未安装各类运行包，可以在pycharm调试框里进行下载，有install package的字样）  
3.将代码中24-26行代码中  
WIND_CSV = r"D:\life5\其他\非线性\大作业\代码\WIND_CSV.csv"  
JOB_CSV  = r"D:\life5\其他\非线性\大作业\代码\JOB_CSV.csv"  
NODE_CSV = r"D:\life5\其他\非线性\大作业\代码\NODE_CSV.csv"  
三个文件地址改为你所下载的三个文件地址  

输出目录: results  
1.figures        论文图表  
2.metrics.txt     定量结果对比表，含消融实验  
3.*.npy           中间数据缓存  
