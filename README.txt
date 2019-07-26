1. 项目使用的库

     如果想运行报告中代码重现模型结果，你需要安装如下库：
          conda install scikei-learn
          conda install -c conda-forge xgboost
    
       项目中还用到一些常见的库，例如pandas，numpy，matplotlib，seaborn等，如果没 有安装，请使用’conda install package’命令安装后使用。

2. 项目机器硬件
   
      该项目在MacBook Air上运行，该机器硬件信息如下：

  型号名称：	MacBook Air
  型号标识符：	MacBookAir7,2
  处理器名称：	Intel Core i5
  处理器速度：	1.8 GHz
  处理器数目：	1
  核总数：	2
  L2 缓存（每个核）：	256 KB
  L3 缓存：	3 MB
  内存：	8 GB
  Boot ROM 版本：	MBA71.0178.B00
  SMC 版本（系统）：	2.27f2
  序列号（系统）：	C02VN0FXJ1WL
  硬件 UUID：	EFC8E0C0-ED4F-55C4-BBB3-AABEBE590FFF

3. 项目机器操作系统
    
     应用Mac OS操作系统（版本10.14）

4. 项目训练时间
    
     XGBoost模型运行时间1420.664636 s

5. 项目数据集

      在运行代码前需要下载和解压 Kaggle（链接 https://www.kaggle.com/c/rossmann-store-sales/data） 上的数据集。同时在提交文件中也附上了这四个数据集train.csv、store.csv、test.csv和sample_submission.csv 。项目中还用到一个上述链接未提供的额外数据集，可以通过（链接 https://github.com/entron/entity-embedding-rossmann/blob/master/store_states.csv）获得。
