# [Link](udemy.com/course/the-ultimate-hands-on-hadoop-tame-your-big-data/) for the course 
Contents from the BigData course

# The-Ultimate-Hands-On-Hadoop-Tame-your-Big-Data
Hadoop tutorial with MapReduce, HDFS, Spark, Flink, Hive, HBase, MongoDB, Cassandra, Kafka + more! Over 25 technologies.

### Acknowledgements

Course work and notes from Udemy Course by Frank Kane.

## **Topics/Technologies covered:**

#### Core
- [x] Introduction to the Hadoop Eco-system
- [x] YARN
- [x] HDFS
- [x] MapReduce
- [x] Pig
- [x] Spark
- [x] Hive
- [x] Tez
- [x] Mesos
- [x] Zookeeper
- [x] Oozie
#### Querying
- [x] Apache Drill
- [x] Apache Phoenix
- [x] Presto
#### Ingestion
- [x] Sqoop
- [x] Kafka
- [x] Flume
#### NoSQL Databases
- [x] HBase
- [x] Cassandra
- [x] MongoDB
#### Streaming
- [x] Spark Streaming
- [x] Storm
- [x] Flink
#### Other
Apache Zepplin, Impala, Accumulo, Redis, Ignite, Elasticsearch, Kinesis, Apache NiFi, Falcon, Apache Slider.

Notes for self->

If latency is concern where we want to responses in milisecond, We could used HBase or Cassandra.
If queries can be based on day-old data/minute-old, then use Oozie-scheduled jobs with Hive/Pig/Spark
But if its real-time, we can use Spark Streaming/Storm/Flink with Kafka or Flume.
