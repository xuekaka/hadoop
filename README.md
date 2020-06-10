# 大数据实习任务

### HDFS操作
每位同学完成基本的 HDFS Shell 命令操作。
HDFS 中创建大批量小文件，分析小文件的 Block 是多大，使用hdfs存储小文件的缺点是什么，你什么改进措施吗？
### MapReduce编程
每位同学在新概念英语第二册上完成 word count。  
tmdb:  
在电影数据集 tmdb-5000-movie-dataset 上完成至少一个任务，比如计算出每个公司的高分电影（得分6.5以上）总收入。  
matrix:  
给出以“风筝网络”network.jpg为输入时的运算结果。（已给出矩阵的邻接矩阵adj.txt）实现矩阵乘法。算出该图的邻接矩阵自乘的结果。  

### Hive Pig 
将time-series-19-covid-combined_csv.csv数据导入Hive和Pig数据库，完成以下三个查询。

1. 该病毒在全球、中国湖北、中国大陆其它省份的病死率分别是多少(总共计算3个病死率)？病死率=病死人数/确诊人数
2. 确诊人数超过5000的国家/地区中病死率前三的国家/地区是哪些？
3. 你感兴趣的查询/统计。

### Hbase
要求同上

### MongoDB
将CORD-19-research.zip数据集导入MongDB并完成两个有意义的查询。

### Spark
1. Spark RDD：对给出的莎士比亚文集Shakespere.txt进行wordcount（注：文件中包含特殊字符，请先进行过滤操作仅留下英文字符）
2. Spark SQL：重现你第二次作业中 在tmdb数据上实现的查询功能。
3. Spark MLlib: 使用TitanicTrainTest.zip中的训练集训练一个分类模型(比如决策树)，并且给出在测试集上的正确率。


### GraphX
用GraphX再次实现PageRank。

### MLlib

数据集和任务来自2018腾讯广告算法大赛。利用spark MLlib训练模型(自选)完成预测并计算评估指标(自选)。
