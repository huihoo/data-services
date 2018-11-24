## 数据库、存储、大数据
PostgreSQL、Cassandra、Ceph 是 RDBMS、NoSQL、Storage 的三个典型代表，我们将更多围绕它们展开数据库、存储的交流。

### PostgreSQL
PostgreSQL 是一种非常复杂的对象-关系型数据库管理系统（ORDBMS），也是目前功能最强大，特性最丰富和最复杂的自由开源数据库系统。

### Cassandra
Apache Cassandra 是一套开源分布式健值存储系统，它最初由Facebook开发，用于储存特别大的数据。

### Ceph
Ceph 是一个 Linux PB 级分布式文件系统，它还是具有企业级功能的统一存储解决方案。

Ceph之父Sage：Ceph要做分布式存储领域的Linux。

### 大数据
大数据参考路线图：

简单讲，可分为以下三种主要方式：
* 1、Hadoop 离线批处理、MapReduce任务处理；
* 2、Spark 实时流处理、RDD内存计算；
* 3、Hadoop和Spark 混合模式。

Hodoop和Spark的融合：

Spark adds in-Memory Compute for ETL, Machine Learning and Data Science Workloads to Hadoop.

### Hadoop
Apache Hadoop 是大数据生态的事实标准。

### Spark
Apache Spark：新一代大数据解决方案，常与Hadoop一起组成完整的大数据基础设施。

Spark 是用Scala和Java语言编写的一套分布式内存计算系统，它的核心抽象模型是 RDD (Resilient Distributed Dataset，弹性分布式数据集)，围绕 RDD 构建了一系列分布式 API，可以直接对数据集进行分布式处理。


### Alluxio
Alluxio是一个内存分布式文件系统，其作用是在Apache Spark或MapReduce等集群框架中实现内存级速度的跨集群文件共享。

下一代数据湖技术：Alluxio + Spark将极为重要。

可简单理解：Alluxio负责内存数据存储，而Spark负责内存数据计算。

### Druid
Druid 是一个为OLAP设计的开源(Apache v2)事件流分析引擎。

Druid 最初主要应用于广告市场的在线数据处理领域，可以让用户基于时间序列数据做任意和互动的分析。一些关键的功能包括低延迟事件处理、快速聚合、近似和精确的计算。

Druid 的核心是一个使用专门的节点来处理每个部分的问题自定义的数据存储。实时分析基于实时管理（JVM）节点来处理，最终数据会存储在历史节点中负责老的数据。代理节点直接查询实时和历史节点，给用户一个完整的事件信息。测试表明50万事件数据能够在一秒内处理完成，并且每秒处理能力可以达到100万的峰值，Druid作为在线广告处理、网络流量和其他的活动流的理想实时处理平台。

### ODPi
ODPi: 开放的大数据生态系统，Linux基金会发起。

ODPi认证和兼容性产品：
* Hortonworks Data Platform
* Pivotal HD
* IBM Open Platform
* Infosys Information Platform

### 文档
* [Stream Processing Frameworks and Products as Game Changers for the Internet of Things](http://docs.huihoo.com/javaone/2015/CON1534-Stream-Processing-Frameworks-and-Products-as-Game-Changers-for-the-Internet-of-Things.pdf)
* [Java, Scala, and Friends: Touring the Java Bedrock of Big Data](http://docs.huihoo.com/javaone/2015/CON3525-Java-Scala-and-Friends-Touring-the-Java-Bedrock-of-Big-Data.pdf)
* [Securing Your Big Data Environment](http://docs.huihoo.com/blackhat/usa-2015/us-15-Gaddam-Securing-Your-Big-Data-Environment.pdf)
* [Securing the Big Data Ecosystem](http://docs.huihoo.com/rsaconference/usa-2014/stu-t07a-securing-the-big-data-ecosystem.pdf)
* [Harnessing Big Data for Application Security Intelligence](http://docs.huihoo.com/rsaconference/usa-2014/spo3-t08-good-guys-vs-bad-guys-using-big-data-to-counteract-advanced-threats.pdf)
* [Security Business Intelligence– Big Data for Faster Detection/Response](http://docs.huihoo.com/rsaconference/usa-2014/stu-r02b-security-business-intelligence-big-data-for-faster-detection-response.pdf)
* [MADlib: Big Data Machine Learning in PostgreSQL](http://docs.huihoo.com/postgresql/pgcon/2012/MADlib-Big-Data-Machine-Learning-in-PostgreSQL.pdf)

### 图集
![Big Data Landscape](https://wiki.huihoo.com/images/5/5b/Big-Data-Landscape-2018.jpg)

![ODPi](https://wiki.huihoo.com/images/0/0d/ODPi.png)ODPi大数据生态系统

![HDP](https://wiki.huihoo.com/images/3/39/Hortonworks-data-platform.png)
HDP

![HDF](https://wiki.huihoo.com/images/2/28/Hortonworks-HDF-Data-in-Motion-Plaform.png)HDF

### 链接
* [PostgreSQL](http://postgresql.org)
* [Cassandra](http://cassandra.apache.org)
* [Ceph](https://ceph.com/)
* [Hadoop](http://hadoop.apache.org)
* [Spark](http://spark.apache.org/)
* [Alluxio](https://www.alluxio.org/)
* [Druid](http://druid.io/)
* [ODPi](http://www.odpi.org/)

## 许可协议 License

课程和课件采用CC

[![CC](http://wiki.huihoo.com/images/4/4e/CC-BY-SA_3.0-88x31.png)](http://wiki.huihoo.com/wiki/CC-BY-SA_3.0)

代码采用Apache v2

## 赞助与支持
本服务教程为免费教程，若需要得到更多技术支持，可通过赞助我们的方式获得，谢谢。

![灰狐会员](http://wiki.huihoo.com/images/2/25/Zsxq.jpg)

[灰狐的朋友们更多权益](https://wiki.huihoo.com/wiki/%E7%81%B0%E7%8B%90%E4%BC%9A%E5%91%98)
