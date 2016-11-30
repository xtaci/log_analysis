# log analysis
日志分析资料汇集

## scenario
![scenario](log.png)

## hadoop
* http://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-common/SingleCluster.html  -- 单节点hdfs部署

## kafka
* https://kafka.apache.org/documentation   --kafka官方文档
* https://www.elastic.co/blog/just-enough-kafka-for-the-elastic-stack-part1  -- es和kafka的最佳实践
* https://www.elastic.co/blog/just-enough-kafka-for-the-elastic-stack-part2
* https://github.com/travisjeffery/jocko   --golang的kafka复刻

## hive
* https://cwiki.apache.org/confluence/display/Hive/GettingStarted -- hive配置
* https://cwiki.apache.org/confluence/display/Hive/LanguageManual --hive的SQL手册
* https://github.com/xtaci/json2hive -- 通过json构造hive schema

## metastore
* https://hub.docker.com/_/mysql/  -- 可以给hive用的mysql镜像
* https://issues.apache.org/jira/secure/attachment/12471108/HiveMetaStore.pdf   -- metastore结构
* https://cwiki.apache.org/confluence/display/Hive/AdminManual+MetastoreAdmin -- metastore配置
* https://cwiki.apache.org/confluence/display/Hive/Hive+Schema+Tool -- schematool

## spark
* https://cwiki.apache.org/confluence/display/Hive/Hive+on+Spark%3A+Getting+Started -- hive和spark集成
* http://spark.apache.org/docs/latest/spark-standalone.html -- spark配置

## elasticsearch
* https://www.elastic.co/guide/en/elasticsearch/hadoop/current/hive.html --es和hive的集成
* https://www.elastic.co/blog/found-sizing-elasticsearch -- es索引规划，容量规划
* https://www.elastic.co/blog/performance-indexing-2-0 -- es索引
* https://www.elastic.co/blog/found-elasticsearch-from-the-bottom-up --es内部原理
* https://www.elastic.co/guide/en/elasticsearch/reference/current/indices-templates.html -- index模板
* https://www.elastic.co/blog/found-elasticsearch-in-production --es生产部署
* https://www.smashingmagazine.com/2012/05/stop-redesigning-start-tuning-your-site/
* https://www.elastic.co/blog/customizing-your-document-routing -- es读取优化
* https://www.elastic.co/videos/big-data-search-and-analytics
* https://www.elastic.co/blog/disk-based-field-data-a-k-a-doc-values
* https://aphyr.com/posts/288-the-network-is-reliable
* https://aphyr.com/posts/281-call-me-maybe-carly-rae-jepsen-and-the-perils-of-network-partitions

## s3
* https://www.elastic.co/guide/en/elasticsearch/reference/current/modules-snapshots.html  --es数据备份
* https://www.elastic.co/guide/en/elasticsearch/plugins/5.0/repository-s3.html --es备份到s3的插件
* https://github.com/minio/minio --s3兼容存储

## mongodb:
* https://github.com/mongodb/mongo-hadoop 
* https://github.com/mongodb/mongo-hadoop/wiki/Hive-Usage -- hive和mongodb的集成
* https://docs.mongodb.com/manual/tutorial/deploy-replica-set/ -- mongodb复制集部署
* https://www.mongodb.com/blog/post/using-mongodb-hadoop-spark-part-1-introduction-setup -- mongodb和spark/hive集成
* https://www.mongodb.com/blog/post/using-mongodb-hadoop-spark-part-2-hive-example
* https://www.mongodb.com/blog/post/using-mongodb-hadoop-spark-part-3-spark-example-key-takeaways

## application library
* https://github.com/gliderlabs/logspout -- 采集docker容器的标准输出
* https://github.com/Sirupsen/logrus -- 结构化日志输出
