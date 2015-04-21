## Issues that contain "Out of Memory" or "OOM" or "OutOfMemory" in Spark user mailing list

1. [Re: Out of memory on large RDDs](http://apache-spark-user-list.1001560.n3.nabble.com/Re-Out-of-memory-on-large-RDDs-tp2533.html)

	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code: Yes

2. [Running out of memory Naive Bayes](http://apache-spark-user-list.1001560.n3.nabble.com/Running-out-of-memory-Naive-Bayes-tp4866.html)

	Root cause: Too many features stored in the driver  
	Pattern: Unknown  
	Reproducible: No  

	Even the features are sparse, the conditional probabilities are stored 
in a dense matrix. With 200 labels and 2 million features, you need to 
store at least 4e8 doubles on the driver node. With multiple 
partitions, you may need more memory on the driver. Could you try 
reducing the number of partitions and giving driver more ram and see 
whether it can help

3. [Kafka streaming out of memory](http://apache-spark-user-list.1001560.n3.nabble.com/Kafka-streaming-out-of-memory-tp2639.html)
	
	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	
4. [Serializer or Out-of-Memory issues?](http://apache-spark-user-list.1001560.n3.nabble.com/Serializer-or-Out-of-Memory-issues-tp8533.html)
	
	Occuring phase: reduceByKey()  
	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  

5. [OUT OF MEMORY ERROR: HEAP SPACE](http://apache-spark-user-list.1001560.n3.nabble.com/OUT-OF-MEMORY-ERROR-HEAP-SPACE-tp8698.html)

	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : Yes
	
6. [Out of Memory - Spark Job server](http://apache-spark-user-list.1001560.n3.nabble.com/Out-of-Memory-Spark-Job-server-tp12852.html)


	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
7. [Driver fail with out of memory exception](http://apache-spark-user-list.1001560.n3.nabble.com/Driver-fail-with-out-of-memory-exception-tp14188.html)

	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
8. [Running out of memory on livejournal](http://apache-spark-user-list.1001560.n3.nabble.com/Running-out-of-memory-on-livejournal-tp18890.html)

	Occuring phase: GropuLoader + graph.pageRank()
	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : Yes
	
9. [MLlib Logistic Regression run out of memory](http://apache-spark-user-list.1001560.n3.nabble.com/MLlib-Logistic-Regression-run-out-of-memory-tp22210.html)

	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
10. [Executor out of memory and gets killed](http://apache-spark-user-list.1001560.n3.nabble.com/Executor-out-of-memory-and-gets-killed-tp22419.html)

	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
11. [out of memory errors -- per core memory limits?](http://apache-spark-user-list.1001560.n3.nabble.com/out-of-memory-errors-per-core-memory-limits-tp12565.html)

	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No

12. [help me: Out of memory when spark streaming](http://apache-spark-user-list.1001560.n3.nabble.com/help-me-Out-of-memory-when-spark-streaming-tp5854.html)

	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
13. [Out of memory exception in MLlib's naive baye's classification training](http://apache-spark-user-list.1001560.n3.nabble.com/Out-of-memory-exception-in-MLlib-s-naive-baye-s-classification-training-tp14809.html)

	Occuring phase: combineByKey() or collect()
	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
14. [Meaning of persistence levels -- setting persistence causing out of memory errors with pyspark](http://apache-spark-user-list.1001560.n3.nabble.com/Meaning-of-persistence-levels-setting-persistence-causing-out-of-memory-errors-with-pyspark-tp17412.html)

	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
15. [Spark SQL 1.1.0 - large insert into parquet runs out of memory](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-SQL-1-1-0-large-insert-into-parquet-runs-out-of-memory-tp14924.html)


	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
16. [Common crawl parsing has high fan out and runs out of memory](http://apache-spark-user-list.1001560.n3.nabble.com/Common-crawl-parsing-has-high-fan-out-and-runs-out-of-memory-tp21708.html) (*)


	Root cause: ArrayList in Java flatMap()  
	Pattern: Large accumulated results  
	Reproducible: Yes (large flatMap())  
	Source code : No
	
	The code works, but it requires almost 12G of memory per ParseWarc.call, because even though I know how to read one record a time from the gzip, and I can output one record a time, the flatMap api requires that the whole Iterable is created in memory before being returned. 
	
17. [Long running time for GraphX pagerank in dataset com-Friendster](http://apache-spark-user-list.1001560.n3.nabble.com/Long-running-time-for-GraphX-pagerank-in-dataset-com-Friendster-tp4511.html)


	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
18. [distinct on huge dataset](http://apache-spark-user-list.1001560.n3.nabble.com/distinct-on-huge-dataset-tp3025.html)


	Root cause: Distinct() on large dataset  
	Pattern: Improper data partition   
	Reproducible: Yes
	
19. [Lost executors](http://apache-spark-user-list.1001560.n3.nabble.com/Lost-executors-tp11722.html)


	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
20. [Any issues with repartition?](http://apache-spark-user-list.1001560.n3.nabble.com/Any-issues-with-repartition-tp13462.html)


	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
21. [Partitioning - optimization or requirement?](http://apache-spark-user-list.1001560.n3.nabble.com/Partitioning-optimization-or-requirement-tp3359.html)

	Root cause: Hotspot key (doing unbalanced joins (ie. cardinality of some joined elements much larger than others)  
	Pattern: Hotspot key
	Reproducible: No  
	Source code : No
	
22. [tiers of caching](http://apache-spark-user-list.1001560.n3.nabble.com/tiers-of-caching-tp8927.html)

	Root cause: (graphx liberally cache RDDs for efficiency, which makes sense. however it can also leave a long trail of unused yet cached RDDs, that might push other RDDs out of memory.)    
	Pattern: Too many rdds cached in memory  
	Reproducible: No   
	Source code : No
	
23. [Buffering for Socket streams](http://apache-spark-user-list.1001560.n3.nabble.com/Buffering-for-Socket-streams-tp22164.html)

	Root cause: (writing large files to HDFS via Socket streamer)  
	Pattern: Unknown
	Reproducible: No  
	Source code : No
	
24. [configuration needed to run twitter(25GB) dataset](http://apache-spark-user-list.1001560.n3.nabble.com/configuration-needed-to-run-twitter-25GB-dataset-tp11044.html)
	
	Occuring phase: GraphX iteration large graph.  
	Root cause: Unknown  
	Pattern: Unknown
	Reproducible: No  
	Source code : No
	
25. [how to debug ExecutorLostFailure](http://apache-spark-user-list.1001560.n3.nabble.com/how-to-debug-ExecutorLostFailure-tp15646.html)

	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
29. [OutOfMemory of spark streaming on standalone in 5 minutes, but run normal on local mode](http://apache-spark-user-list.1001560.n3.nabble.com/OutOfMemory-of-spark-streaming-on-standalone-in-5-minutes-but-run-normal-on-local-mode-tp21352.html)

	Root cause: Input data => socketTextStream => store data onto HDFS  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
30. [Spark streaming](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-streaming-tp22255.html)

	Root cause: Unknown
	Pattern: Unknown  
	Reproducible: No  
	Source code : No

31. [How to join two PairRDD together?](http://apache-spark-user-list.1001560.n3.nabble.com/How-to-join-two-PairRDD-together-tp12729.html)

	Symptom: adding the same key to every element, and joining  
	Root cause: Unknown
	Pattern: Unknown  
	Reproducible: No  
	Source code : No

35. [[SQL] Set Parquet block size?](http://apache-spark-user-list.1001560.n3.nabble.com/SQL-Set-Parquet-block-size-tp16039.html)

	Symptom: Out of Memory issues when writing parquet files. The rdd we are saving to parquet have a fairly high number of columns (in the thousands, around 3k for the moment).   
	Root cause: Unknown
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
37. [trouble with broadcast variables on pyspark](http://apache-spark-user-list.1001560.n3.nabble.com/trouble-with-broadcast-variables-on-pyspark-tp1301.html)

	Symptom: A ~1GB array seems to be blowing up beyond the size of the driver machine's memory when it's pickled. I've tried to get around this by broadcasting smaller chunks of it one at a time.   
	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No

44. [spark streaming rate limiting from kafka](http://apache-spark-user-list.1001560.n3.nabble.com/spark-streaming-rate-limiting-from-kafka-tp8590.html)

	Symptom: accumulate a lot on kafka topic-partitions.   
	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
45. [RDD join: composite keys](http://apache-spark-user-list.1001560.n3.nabble.com/RDD-join-composite-keys-tp8696.html)

	Symptom: accumulate a lot on kafka topic-partitions.   
	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
46. [AppMaster OOME on YARN](http://apache-spark-user-list.1001560.n3.nabble.com/AppMaster-OOME-on-YARN-tp12612.html)
	
	Symptom: groupBy() .mapValues().fold()   
	Root cause: Unknown  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	

48. [Yarn Driver OOME (Java heap space) when executors request map output locations](http://apache-spark-user-list.1001560.n3.nabble.com/Yarn-Driver-OOME-Java-heap-space-when-executors-request-map-output-locations-tp13827.html)
	
	Symptom: the driver appears to be making 500 (5gb of data) copies of this data to send out and running out of memory.  
	Root cause: Dirver generates large dataset  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
49. [MLLib ALS question](http://apache-spark-user-list.1001560.n3.nabble.com/MLLib-ALS-question-tp15420.html) (Further study)

	Symptom: The current ALS 
implementation constructs all subproblems in memory. With rank=10, 
that means (6.5M + 2.5M) * 10^2 / 2 * 8 bytes = 3.5GB. The ratings 
need 2GB, not counting the overhead.   ALS still needs to load and deserialize the in/out blocks (one by one) 
from disk and then construct least squares subproblems. All happen in 
RAM. The final model is also stored in memory.  
	Root cause: Large data loaded into memory, intermediate computing results. 
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
50. [Accumulator question](http://apache-spark-user-list.1001560.n3.nabble.com/Accumulator-question-tp15715.html) (Further study)

	Symptom: we're gathering data from repeated queries using some relatively sizable accumulators; at the moment, we're creating one per query, and running out of memory after far too few queries.
	Root cause: Large accumulated results in Accumulators.  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
51. [Lag function equivalent in an RDD](http://apache-spark-user-list.1001560.n3.nabble.com/Lag-function-equivalent-in-an-RDD-tp16448.html)

	Symptom: I have tried reduceByKey and then splitting the List of position in 
tuples.   
	Root cause: Hotspot key, one vehicle has a huge amount of data that could fail. 
	Pattern: Unknown  
	Reproducible: No  
	Source code : No

53. [JVM Memory Woes](http://apache-spark-user-list.1001560.n3.nabble.com/JVM-Memory-Woes-tp19496.html)
	
	Symptom: It is a filter job that creates the error above, not the reduceByKey.  	Root cause: probably reduceByKey(), although authors claim the causes exist in filter()  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No


56. [Memory allocation in the driver](http://apache-spark-user-list.1001560.n3.nabble.com/Memory-allocation-in-the-driver-tp8406.html)

	
	Symptom: call to "b.first" will cause the spark driver to allocate a VERY large piece of memory. The first item of the first partition is very small (less than 200 bytes). However, the size of the entire first partition was about 380 MB.  
	Root cause: large data collected() by driver, although each partition is small.
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
57. [GC issues](http://apache-spark-user-list.1001560.n3.nabble.com/GC-issues-tp1422.html)
	
	Symptom: OOM  
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	

59. [Spark limitations question](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-limitations-question-tp3296.html) (Further study)

	Symptom:  join Base to Skewed, works well on all but one of the nodes on the cluster 
	Pattern: Skewed data  
	Reproducible: No  
	Source code : No

60. [Kyro serialization slow and runs OOM](http://apache-spark-user-list.1001560.n3.nabble.com/Kyro-serialization-slow-and-runs-OOM-tp1073.html)

	
	Symptom: I load my dataset, transform it with some one to one transformations, and try to cache the eventual RDD - it runs really slow and then runs out of memory.   
	Pattern: Large data cached  
	Reproducible: No  
	Source code : No

65. [Pyspark Memory Woes](http://apache-spark-user-list.1001560.n3.nabble.com/Pyspark-Memory-Woes-tp2538.html)

	Symptom: Discussion    
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
66. [Doubts regarding Shark](http://apache-spark-user-list.1001560.n3.nabble.com/Doubts-regarding-Shark-tp5756.html)

	Symptom: Discussion    
	Pattern: Unknown  
	Reproducible: No  
	Source code : No
	
67. [advice on maintaining a production spark cluster?](http://apache-spark-user-list.1001560.n3.nabble.com/advice-on-maintaining-a-production-spark-cluster-tp5848.html)

	Symptom: Running out of memory on the driver side (esp. with large broadcast variables)   
	Pattern: Driver is going to broadcast large dataset  
	Reproducible: No  
	Source code : No

69. [pyspark join crash](http://apache-spark-user-list.1001560.n3.nabble.com/pyspark-join-crash-tp6938.html)

	I think the problem is that once unpacked in Python, the objects take considerably more space, as they are stored as Python objects in a Python dictionary. Take a look at python/pyspark/join.py and combineByKey in python/pyspark/rdd.py. We should probably try to store these in serialized form.
	
72. ["Spilling in-memory..." messages in log even with MEMORY_ONLY](http://apache-spark-user-list.1001560.n3.nabble.com/Spilling-in-memory-messages-in-log-even-with-MEMORY-ONLY-tp10723.html)

	These messages are actually not about spilling the RDD, they're about spilling intermediate state in a reduceByKey, groupBy or other operation whose state doesn't fit in memory. We have to do that in these cases to avoid going out of memory. You can minimize spilling by having more reduce tasks though, which will mean less data per task. 
	
73. [Understanding RDD.GroupBy OutOfMemory Exceptions](http://apache-spark-user-list.1001560.n3.nabble.com/Understanding-RDD-GroupBy-OutOfMemory-Exceptions-tp11427.html) (Further study, groupByKey())
	
	Symptom: OOM in groupByKey() but no error in reduceByKey()
	Pattern:  large input record, 
	Reproducible: No  
	Source code : No
	
	The groupBy operator in Spark is not an aggregation operator (e.g. in SQL where you do select sum(salary) group by age...) - there are separate more efficient operators for aggregations. Currently groupBy requires that all of the values for one key can fit in memory. In your case, it's possible you have a single key with a very large number of values, given that your count seems to be failing on a single task.

75. [Question regarding spark data partition and coalesce. Need info on my use case.](http://apache-spark-user-list.1001560.n3.nabble.com/Question-regarding-spark-data-partition-and-coalesce-Need-info-on-my-use-case-tp12214.html)

		
	Symptom: Without using coalesce() or repartition() on the input data spark executes really slow and fails with out of memory exception.  
	Pattern:  Unknown
	Reproducible: No  
	Source code : No
	
76. [pyspark/yarn and inconsistent number of executors](http://apache-spark-user-list.1001560.n3.nabble.com/pyspark-yarn-and-inconsistent-number-of-executors-tp12406.html)

	Pattern:  Unknown  
	Reproducible: No  
	Source code : No
	
77. [Bulk-load to HBase](http://apache-spark-user-list.1001560.n3.nabble.com/Bulk-load-to-HBase-tp14667.html) (Further study)

	Symptom: OOM on mapPartitionsWithIndex() for splitKeys, I have to merge the byte[]s that have the same key. 
	Pattern:  Large accumulated results
	Reproducible: No  
	Source code : No
	
	
	The problem is that you will first collect and allocate many small byte[] in memory, and then merge them. If the total size of the byte[]s is very large, you run out of memory, 

78. [Setup an huge Unserializable Object in a mapper](http://apache-spark-user-list.1001560.n3.nabble.com/Setup-an-huge-Unserializable-Object-in-a-mapper-tp14817.html) (Further study)
			
	Symptom: getTree function in each iterator of map()  
	Pattern:  Unknown
	Reproducible: No  
	Source code : No
	
79. [driver memory management](http://apache-spark-user-list.1001560.n3.nabble.com/driver-memory-management-tp15305.html)

	Symptom: driver OOM  
	Pattern:  Unknown  
	Reproducible: No  
	Source code : No
	
81. [something about rdd.collect](http://apache-spark-user-list.1001560.n3.nabble.com/something-about-rdd-collect-tp16451.html)

	Symptom: driver OOM  
	Pattern:  Unknown  
	Reproducible: No  
	Source code : No
	
83. [MLLib /ALS : java.lang.OutOfMemoryError: Java heap space](http://apache-spark-user-list.1001560.n3.nabble.com/MLLib-ALS-java-lang-OutOfMemoryError-Java-heap-space-tp20584.html)
	
	Symptom: shuffle buffer + storage buffer > limit 
	Pattern:  Unknown  
	Reproducible: No  
	Source code : No

89. [Spark Processing Large Data Stuck](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-Processing-Large-Data-Stuck-tp8075.html)
		
	Symptom: Java.deserialization.buffer + ExeternalAppendOnlyMap  
	Pattern:  Large buffer
	Reproducible: No  
	Source code : No

	
90. [memory leak query](http://apache-spark-user-list.1001560.n3.nabble.com/memory-leak-query-tp8961.html)
			
	Symptom: Loop of rdd.count()  
	Pattern:  Unknown  
	Reproducible: No  
	Source code : No


96. [OOM with groupBy + saveAsTextFile](http://apache-spark-user-list.1001560.n3.nabble.com/OOM-with-groupBy-saveAsTextFile-tp17891.html) (Further study)
			
	Symptom: GroupBy + saveAsTextFile, The value after groupBy() is too large  
	Pattern:  Unknown  
	Reproducible: No  
	Source code : No

	
97. [trouble with "join" on large RDDs](http://apache-spark-user-list.1001560.n3.nabble.com/trouble-with-join-on-large-RDDs-tp3864.html)

	Pattern:  Unknown  
	Reproducible: No  
	Source code : No
	
98. [What should happen if we try to cache more data than the cluster can hold in memory?](http://apache-spark-user-list.1001560.n3.nabble.com/What-should-happen-if-we-try-to-cache-more-data-than-the-cluster-can-hold-in-memory-tp11175.html)
	
	Symptom: Individual partitions were too big to fit in memory.  
	Pattern:  Improper data partition
	Reproducible: No  
	Source code : No

99. [Spark app throwing java.lang.OutOfMemoryError: GC overhead limit exceeded](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-app-throwing-java-lang-OutOfMemoryError-GC-overhead-limit-exceeded-tp11350.html)

	Pattern:  Unknown  
	Reproducible: No  
	Source code : No
	
101. [java.lang.OutOfMemoryError: Requested array size exceeds VM limit](http://apache-spark-user-list.1001560.n3.nabble.com/java-lang-OutOfMemoryError-Requested-array-size-exceeds-VM-limit-tp12993.html)

	Pattern:  Unknown  
	Reproducible: No  
	Source code : No
	
102. [processing large number of files](http://apache-spark-user-list.1001560.n3.nabble.com/processing-large-number-of-files-tp15429.html)
	
	Symptom: large array/model in the driver 
	Pattern:  Large data generated in the driver
	Reproducible: No  
	Source code : No
	
103. [RowMatrix PCA out of heap space error](http://apache-spark-user-list.1001560.n3.nabble.com/RowMatrix-PCA-out-of-heap-space-error-tp16305.html)

	
	Pattern:  Large matrix in the driver 
	Reproducible: No  
	Source code : No
	
105. [Problems with broadcast large datastructure](http://apache-spark-user-list.1001560.n3.nabble.com/Problems-with-broadcast-large-datastructure-tp331.html)

	Symptom: Broadcast large data
	Pattern:  Large data cached in memory
	Reproducible: No  
	Source code : No
	
106. [OOM - Help Optimizing Local Job](http://apache-spark-user-list.1001560.n3.nabble.com/OOM-Help-Optimizing-Local-Job-tp643.html) (Further study)
	
	Symptom: combineValuesByKey()
	Pattern:  Large data cached in memory
	Reproducible: No  
	Source code : No
	
107. [Spark streaming questions](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-streaming-questions-tp1494.html) (Further study)

	Symptom: DStream.persist() constantly  
	Pattern:  Large data cached in memory
	Reproducible: No  
	Source code : No
	
108. [shuffle memory requirements](http://apache-spark-user-list.1001560.n3.nabble.com/shuffle-memory-requirements-tp4048.html)

	Symptom: partitionBy()
	Pattern:  Unknown
	Reproducible: No  
	Source code : No
	

111. [OutofMemoryError when generating output](http://apache-spark-user-list.1001560.n3.nabble.com/OutofMemoryError-when-generating-output-tp12847.html)

	Symptom: distinct().countByKey()  
	Pattern:  Unknown
	Reproducible: No  
	Source code : No
	

113. [Getting java.lang.OutOfMemoryError when calling mkString on a parition](http://apache-spark-user-list.1001560.n3.nabble.com/Getting-java-lang-OutOfMemoryError-when-calling-mkString-on-a-parition-tp19527.html) (Further study)
		
	Symptom: constant ++ sampleItem, partitionedHeader(header, index) ++ rows
	Pattern:  Unknown
	Reproducible: No  
	Source code : No
	
114. [newbie : java.lang.OutOfMemoryError: Java heap space](http://apache-spark-user-list.1001560.n3.nabble.com/newbie-java-lang-OutOfMemoryError-Java-heap-space-tp365.html)
115. [HBase row count](http://apache-spark-user-list.1001560.n3.nabble.com/HBase-row-count-tp2023.html)
116. [Fwd: Spark - ready for prime time?](http://apache-spark-user-list.1001560.n3.nabble.com/Fwd-Spark-ready-for-prime-time-tp4064.html)
117. [extremely slow k-means version](http://apache-spark-user-list.1001560.n3.nabble.com/extremely-slow-k-means-version-tp4489.html)
118. [Join : Giving incorrect result](http://apache-spark-user-list.1001560.n3.nabble.com/Join-Giving-incorrect-result-tp6910.html)
119. [Comparative study](http://apache-spark-user-list.1001560.n3.nabble.com/Comparative-study-tp8918.html)
120. [Debugging cluster stability, configuration issues](http://apache-spark-user-list.1001560.n3.nabble.com/Debugging-cluster-stability-configuration-issues-tp12591.html)
121. [Broadcast failure with variable size of ~ 500mb with "key already cancelled ?"](http://apache-spark-user-list.1001560.n3.nabble.com/Broadcast-failure-with-variable-size-of-500mb-with-key-already-cancelled-tp17200.html)
122. [Spark streaming fault tolerance question](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-streaming-fault-tolerance-question-tp18930.html)
123. [Help: WARN AbstractNioSelector: Unexpected exception in the selector loop. java.lang.OutOfMemoryError: Java heap space](http://apache-spark-user-list.1001560.n3.nabble.com/Help-WARN-AbstractNioSelector-Unexpected-exception-in-the-selector-loop-java-lang-OutOfMemoryError-Je-tp8633.html)
124. [spark-streaming "Could not compute split" exception](http://apache-spark-user-list.1001560.n3.nabble.com/spark-streaming-Could-not-compute-split-exception-tp13820.html)
125. [Lost TID: Loss was due to fetch failure from BlockManagerId](http://apache-spark-user-list.1001560.n3.nabble.com/Lost-TID-Loss-was-due-to-fetch-failure-from-BlockManagerId-tp8607.html)
126. [Spark on Yarn probably trying to load all the data to RAM](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-on-Yarn-probably-trying-to-load-all-the-data-to-RAM-tp17908.html)
127. [KMeans Input Format](http://apache-spark-user-list.1001560.n3.nabble.com/KMeans-Input-Format-tp11654.html)
128. [Help alleviating OOM errors](http://apache-spark-user-list.1001560.n3.nabble.com/Help-alleviating-OOM-errors-tp8534.html)
129. [[Streaming]Executor OOM](http://apache-spark-user-list.1001560.n3.nabble.com/Streaming-Executor-OOM-tp12383.html)
130. [serialization changes -- OOM](http://apache-spark-user-list.1001560.n3.nabble.com/serialization-changes-OOM-tp13843.html)
131. [OOM for HiveFromSpark example](http://apache-spark-user-list.1001560.n3.nabble.com/OOM-for-HiveFromSpark-example-tp21129.html)
132. [Driver OOM while using reduceByKey](http://apache-spark-user-list.1001560.n3.nabble.com/Driver-OOM-while-using-reduceByKey-tp6513.html)
133. [OOM writing out sorted RDD](http://apache-spark-user-list.1001560.n3.nabble.com/OOM-writing-out-sorted-RDD-tp11828.html)
134. [spark master OOME from maxMbInFlight buffers](http://apache-spark-user-list.1001560.n3.nabble.com/spark-master-OOME-from-maxMbInFlight-buffers-tp1441.html)
135. [GroupByKey results in OOM - Any other alternative](http://apache-spark-user-list.1001560.n3.nabble.com/GroupByKey-results-in-OOM-Any-other-alternative-tp7625.html)
136. [Spark on Mesos cause mesos-master OOM](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-on-Mesos-cause-mesos-master-OOM-tp12631.html)
137. [Beginner Question on driver memory issue (OOM).](http://apache-spark-user-list.1001560.n3.nabble.com/Beginner-Question-on-driver-memory-issue-OOM-tp21676.html)
138. [Spark-Shell: OOM: GC overhead limit exceeded](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-Shell-OOM-GC-overhead-limit-exceeded-tp15890.html)
139. [OOM Java heap space error on saveAsTextFile](http://apache-spark-user-list.1001560.n3.nabble.com/OOM-Java-heap-space-error-on-saveAsTextFile-tp12604.html)
140. [pyspark sc.parallelize running OOM with smallish data](http://apache-spark-user-list.1001560.n3.nabble.com/pyspark-sc-parallelize-running-OOM-with-smallish-data-tp9452.html)
141. [[PySpark] large # of partitions causes OOM](http://apache-spark-user-list.1001560.n3.nabble.com/PySpark-large-of-partitions-causes-OOM-tp13155.html)
142. [OOM - Requested array size exceeds VM limit](http://apache-spark-user-list.1001560.n3.nabble.com/OOM-Requested-array-size-exceeds-VM-limit-tp17996.html)
143. [OOM when calling cache on RDD with big data](http://apache-spark-user-list.1001560.n3.nabble.com/OOM-when-calling-cache-on-RDD-with-big-data-tp1894.html)
144. [Running Wordcount on large file stucks and throws OOM exception](http://apache-spark-user-list.1001560.n3.nabble.com/Running-Wordcount-on-large-file-stucks-and-throws-OOM-exception-tp12747.html)
145. [replace ConnectionManager#ackTimeoutMonitor with ScheduledExecutorService to avoid OOME under long timeout](http://apache-spark-user-list.1001560.n3.nabble.com/replace-ConnectionManager-ackTimeoutMonitor-with-ScheduledExecutorService-to-avoid-OOME-under-long-tt-tp18567.html)
146. [What the initial steps to understand root of this OOM exception](http://apache-spark-user-list.1001560.n3.nabble.com/What-the-initial-steps-to-understand-root-of-this-OOM-exception-tp16296.html)
147. [Command exited with code 137](http://apache-spark-user-list.1001560.n3.nabble.com/Command-exited-with-code-137-tp7557.html)
148. [Bug in DISK related Storage level?](http://apache-spark-user-list.1001560.n3.nabble.com/Bug-in-DISK-related-Storage-level-tp17954.html)
149. [how to set spark.executor.memory and heap size](http://apache-spark-user-list.1001560.n3.nabble.com/how-to-set-spark-executor-memory-and-heap-size-tp4719.html)
150. [OutOfMemory in "cogroup"](http://apache-spark-user-list.1001560.n3.nabble.com/OutOfMemory-in-cogroup-tp17349.html)
151. [how spark dstream handles congestion?](http://apache-spark-user-list.1001560.n3.nabble.com/how-spark-dstream-handles-congestion-tp3540.html)
152. [Setting only master heap](http://apache-spark-user-list.1001560.n3.nabble.com/Setting-only-master-heap-tp17047.html)
153. [How to correctly extimate the number of partition of a graph in GraphX](http://apache-spark-user-list.1001560.n3.nabble.com/How-to-correctly-extimate-the-number-of-partition-of-a-graph-in-GraphX-tp17903.html)
154. [[0.9.0] MEMORY_AND_DISK_SER not falling back to disk](http://apache-spark-user-list.1001560.n3.nabble.com/0-9-0-MEMORY-AND-DISK-SER-not-falling-back-to-disk-tp1278.html)
155. [Worker re-spawn and dynamic node joining](http://apache-spark-user-list.1001560.n3.nabble.com/Worker-re-spawn-and-dynamic-node-joining-tp5712.html)
156. [Is there a way to limit the sql query result size?](http://apache-spark-user-list.1001560.n3.nabble.com/Is-there-a-way-to-limit-the-sql-query-result-size-tp18316.html)
157. [Manually trigger RDD map function without action](http://apache-spark-user-list.1001560.n3.nabble.com/Manually-trigger-RDD-map-function-without-action-tp21094.html)
158. [Shuffle file not found Exception](http://apache-spark-user-list.1001560.n3.nabble.com/Shuffle-file-not-found-Exception-tp1337.html)
159. [GroupBy Key and then sort values with the group](http://apache-spark-user-list.1001560.n3.nabble.com/GroupBy-Key-and-then-sort-values-with-the-group-tp14455.html)
160. [Multiple Spark Streaming receiver model](http://apache-spark-user-list.1001560.n3.nabble.com/Multiple-Spark-Streaming-receiver-model-tp21002.html)
161. [How to compute RDD[(String, Set[String])] that include large Set](http://apache-spark-user-list.1001560.n3.nabble.com/How-to-compute-RDD-String-Set-String-that-include-large-Set-tp21248.html)
162. [spark streaming and the spark shell](http://apache-spark-user-list.1001560.n3.nabble.com/spark-streaming-and-the-spark-shell-tp3347.html)
163. [Does foreach operation increase rdd lineage?](http://apache-spark-user-list.1001560.n3.nabble.com/Does-foreach-operation-increase-rdd-lineage-tp879.html)
164. [Problem when sorting big file](http://apache-spark-user-list.1001560.n3.nabble.com/Problem-when-sorting-big-file-tp5893.html)
165. [FetchFailed when collect at YARN cluster](http://apache-spark-user-list.1001560.n3.nabble.com/FetchFailed-when-collect-at-YARN-cluster-tp12670.html)
166. [About optimize ALS parameters](http://apache-spark-user-list.1001560.n3.nabble.com/About-optimize-ALS-parameters-tp12824.html)
167. [[Streaming] Cannot get executors to stay alive](http://apache-spark-user-list.1001560.n3.nabble.com/Streaming-Cannot-get-executors-to-stay-alive-tp12940.html)
168. [KafkaInputDStream mapping of partitions to tasks](http://apache-spark-user-list.1001560.n3.nabble.com/KafkaInputDStream-mapping-of-partitions-to-tasks-tp3360.html)
169. [Memory footprint of Calliope: Spark -> Cassandra writes](http://apache-spark-user-list.1001560.n3.nabble.com/Memory-footprint-of-Calliope-Spark-Cassandra-writes-tp7674.html)
170. [yarn + spark deployment issues (high memory consumption and task hung)](http://apache-spark-user-list.1001560.n3.nabble.com/yarn-spark-deployment-issues-high-memory-consumption-and-task-hung-tp21980.html)
171. [Help needed. Not sure how to reduceByKey works in spark](http://apache-spark-user-list.1001560.n3.nabble.com/Help-needed-Not-sure-how-to-reduceByKey-works-in-spark-tp452.html)
172. [Stream RDD to local disk](http://apache-spark-user-list.1001560.n3.nabble.com/Stream-RDD-to-local-disk-tp1045.html)
173. [Need some tutorials and examples about customized partitioner](http://apache-spark-user-list.1001560.n3.nabble.com/Need-some-tutorials-and-examples-about-customized-partitioner-tp2029.html)
174. [Questions about productionizing spark](http://apache-spark-user-list.1001560.n3.nabble.com/Questions-about-productionizing-spark-tp4825.html)
175. [ExternalAppendOnlyMap: Spilling in-memory map](http://apache-spark-user-list.1001560.n3.nabble.com/ExternalAppendOnlyMap-Spilling-in-memory-map-tp6186.html)
176. [Akka disassociation on Java SE Embedded](http://apache-spark-user-list.1001560.n3.nabble.com/Akka-disassociation-on-Java-SE-Embedded-tp6266.html)
177. [Spark 1.0.1 SQL on 160 G parquet file (snappy compressed, made by cloudera impala), 23 core and 60G mem / node, yarn-client mode, always failed](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-1-0-1-SQL-on-160-G-parquet-file-snappy-compressed-made-by-cloudera-impala-23-core-and-60G-mem-d-tp10254.html)
178. [Only master is really busy at KMeans training](http://apache-spark-user-list.1001560.n3.nabble.com/Only-master-is-really-busy-at-KMeans-training-tp12411.html)
179. [JVM heap and native allocation questions](http://apache-spark-user-list.1001560.n3.nabble.com/JVM-heap-and-native-allocation-questions-tp12453.html)
180. [FetchFailedException from Block Manager](http://apache-spark-user-list.1001560.n3.nabble.com/FetchFailedException-from-Block-Manager-tp12689.html)
181. [How to run kmeans after pca?](http://apache-spark-user-list.1001560.n3.nabble.com/How-to-run-kmeans-after-pca-tp14473.html)
182. [Spark Bug? job fails to run when given options on spark-submit (but starts and fails without)](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-Bug-job-fails-to-run-when-given-options-on-spark-submit-but-starts-and-fails-without-tp16618.html)
183. [SparkSubmitDriverBootstrapper and JVM parameters](http://apache-spark-user-list.1001560.n3.nabble.com/SparkSubmitDriverBootstrapper-and-JVM-parameters-tp18290.html)
184. [Setup Remote HDFS for Spark](http://apache-spark-user-list.1001560.n3.nabble.com/Setup-Remote-HDFS-for-Spark-tp19481.html)
185. [Not getting it](http://apache-spark-user-list.1001560.n3.nabble.com/Not-getting-it-tp3316.html)
186. [Local Standalone Application and shuffle spills](http://apache-spark-user-list.1001560.n3.nabble.com/Local-Standalone-Application-and-shuffle-spills-tp2634.html)
187. [something about memory usage](http://apache-spark-user-list.1001560.n3.nabble.com/something-about-memory-usage-tp5107.html)
188. [news20-binary classification with LogisticRegressionWithSGD](http://apache-spark-user-list.1001560.n3.nabble.com/news20-binary-classification-with-LogisticRegressionWithSGD-tp7725.html)
189. [Use Spark streaming to process events in a stream and maintain aggregate statisitics on it](http://apache-spark-user-list.1001560.n3.nabble.com/Use-Spark-streaming-to-process-events-in-a-stream-and-maintain-aggregate-statisitics-on-it-tp12184.html)
190. [Kafka stream receiver stops input](http://apache-spark-user-list.1001560.n3.nabble.com/Kafka-stream-receiver-stops-input-tp12963.html)
191. [closure serialization behavior driving me crazy](http://apache-spark-user-list.1001560.n3.nabble.com/closure-serialization-behavior-driving-me-crazy-tp18468.html)
192. [RDD Blocks skewing to just few executors](http://apache-spark-user-list.1001560.n3.nabble.com/RDD-Blocks-skewing-to-just-few-executors-tp19112.html)
193. [Pig on Spark](http://apache-spark-user-list.1001560.n3.nabble.com/Pig-on-Spark-tp2367.html)
194. [com.google.protobuf out of memory](http://apache-spark-user-list.1001560.n3.nabble.com/com-google-protobuf-out-of-memory-tp6357.html)
195. [Spark Memory Bounds](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-Memory-Bounds-tp6456.html)
196. [Using Spark on Data size larger than Memory size](http://apache-spark-user-list.1001560.n3.nabble.com/Using-Spark-on-Data-size-larger-than-Memory-size-tp6589.html)
197. [RDD with a Map](http://apache-spark-user-list.1001560.n3.nabble.com/RDD-with-a-Map-tp6849.html)
198. [spark.default.parallelism bug?](http://apache-spark-user-list.1001560.n3.nabble.com/spark-default-parallelism-bug-tp12820.html)
199. [Re: spark and mesos issue](http://apache-spark-user-list.1001560.n3.nabble.com/Re-spark-and-mesos-issue-tp14334.html)
200. [How to set Akka frame size](http://apache-spark-user-list.1001560.n3.nabble.com/How-to-set-Akka-frame-size-tp39.html)
201. [Question about RDD cache, unpersist, materialization](http://apache-spark-user-list.1001560.n3.nabble.com/Question-about-RDD-cache-unpersist-materialization-tp7374.html)
202. [Spark 0.9.1 java.lang.outOfMemoryError: Java Heap Space](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-0-9-1-java-lang-outOfMemoryError-Java-Heap-Space-tp7861.html)
203. [spark.cleaner.ttl and spark.streaming.unpersist](http://apache-spark-user-list.1001560.n3.nabble.com/spark-cleaner-ttl-and-spark-streaming-unpersist-tp13826.html)
204. [Spark Disk Usage](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-Disk-Usage-tp3706.html)
205. [How to achieve reasonable performance on Spark Streaming?](http://apache-spark-user-list.1001560.n3.nabble.com/How-to-achieve-reasonable-performance-on-Spark-Streaming-tp7262.html)
206. [pyspark yarn got exception](http://apache-spark-user-list.1001560.n3.nabble.com/pyspark-yarn-got-exception-tp13259.html)
207. [Folding an RDD in order](http://apache-spark-user-list.1001560.n3.nabble.com/Folding-an-RDD-in-order-tp16577.html)
208. [GC Issues with randomSplit on large dataset](http://apache-spark-user-list.1001560.n3.nabble.com/GC-Issues-with-randomSplit-on-large-dataset-tp17695.html)
209. [Spark streaming on YARN?](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-streaming-on-YARN-tp427.html)
210. [Performance and serialization: use case](http://apache-spark-user-list.1001560.n3.nabble.com/Performance-and-serialization-use-case-tp1513.html)
211. [worker keeps getting disassociated upon a failed job spark version 0.90](http://apache-spark-user-list.1001560.n3.nabble.com/worker-keeps-getting-disassociated-upon-a-failed-job-spark-version-0-90-tp2099.html)
212. [Querying a parquet file in s3 with an ec2 install](http://apache-spark-user-list.1001560.n3.nabble.com/Querying-a-parquet-file-in-s3-with-an-ec2-install-tp13737.html)
213. [java.nio.channels.CancelledKeyException](http://apache-spark-user-list.1001560.n3.nabble.com/java-nio-channels-CancelledKeyException-tp17066.html)
214. [Re[2]: HBase 0.96+ with Spark 1.0+](http://apache-spark-user-list.1001560.n3.nabble.com/Re-2-HBase-0-96-with-Spark-1-0-tp13975.html)
215. [Spark SQL Exception](http://apache-spark-user-list.1001560.n3.nabble.com/Spark-SQL-Exception-tp14572.html)
216. [OutOfMemory Error](http://apache-spark-user-list.1001560.n3.nabble.com/OutOfMemory-Error-tp12275.html)
217. [OutOfMemory Error](http://apache-spark-user-list.1001560.n3.nabble.com/OutOfMemory-Error-tp1746.html)
218. [Cannot get rid of OutOfMemory](http://apache-spark-user-list.1001560.n3.nabble.com/Cannot-get-rid-of-OutOfMemory-tp17016.html)
219. [OutOfMemory error in Spark Core](http://apache-spark-user-list.1001560.n3.nabble.com/OutOfMemory-error-in-Spark-Core-tp21179.html)
220. [OutOfMemory : Java heap space error](http://apache-spark-user-list.1001560.n3.nabble.com/OutOfMemory-Java-heap-space-error-tp9091.html)
221. [OutofMemory: Failed on spark/examples/bagel/WikipediaPageRank.scala](http://apache-spark-user-list.1001560.n3.nabble.com/OutofMemory-Failed-on-spark-examples-bagel-WikipediaPageRank-scala-tp6040.html)
222. [mllib svd gives: Java OutOfMemory Error](http://apache-spark-user-list.1001560.n3.nabble.com/mllib-svd-gives-Java-OutOfMemory-Error-tp21982.html)
223. [Scala PCA OutOfMemory error on small number of columns](http://apache-spark-user-list.1001560.n3.nabble.com/Scala-PCA-OutOfMemory-error-on-small-number-of-columns-tp22479.html)
224. [How to efficiently join this two complicated rdds](http://apache-spark-user-list.1001560.n3.nabble.com/How-to-efficiently-join-this-two-complicated-rdds-tp1665.html)
225. [The running time of spark](http://apache-spark-user-list.1001560.n3.nabble.com/The-running-time-of-spark-tp12624.html)
226. [broadcast: OutOfMemoryError](http://apache-spark-user-list.1001560.n3.nabble.com/broadcast-OutOfMemoryError-tp20633.html)
227. [SQL FIlter of tweets (json) running on Disk](http://apache-spark-user-list.1001560.n3.nabble.com/SQL-FIlter-of-tweets-json-running-on-Disk-tp8809.html)
228. [java.lang.OutOfMemoryError: GC overhead limit exceeded](http://apache-spark-user-list.1001560.n3.nabble.com/java-lang-OutOfMemoryError-GC-overhead-limit-exceeded-tp10301.html)
229. [driver memory](http://apache-spark-user-list.1001560.n3.nabble.com/driver-memory-tp10486.html)
230. [When processing vary large date,will the memory have a minimum limit?](http://apache-spark-user-list.1001560.n3.nabble.com/When-processing-vary-large-date-will-the-memory-have-a-minimum-limit-tp13531.html)
231. [KafkaReceiver executor in spark streaming job on YARN suddenly killed by ResourceManager](http://apache-spark-user-list.1001560.n3.nabble.com/KafkaReceiver-executor-in-spark-streaming-job-on-YARN-suddenly-killed-by-ResourceManager-tp20945.html)
232. [Give more Java Heap Memory on Standalone mode](http://apache-spark-user-list.1001560.n3.nabble.com/Give-more-Java-Heap-Memory-on-Standalone-mode-tp10315.html)
233. [OutOfMemoryError with basic kmeans](http://apache-spark-user-list.1001560.n3.nabble.com/OutOfMemoryError-with-basic-kmeans-tp1651.html)
234. [Kafka Streaming - Error Could not compute split](http://apache-spark-user-list.1001560.n3.nabble.com/Kafka-Streaming-Error-Could-not-compute-split-tp8112.html)
235. [Help for the large number of the input data files](http://apache-spark-user-list.1001560.n3.nabble.com/Help-for-the-large-number-of-the-input-data-files-tp8989.html)
236. [Any limitations of spark.shuffle.spill?](http://apache-spark-user-list.1001560.n3.nabble.com/Any-limitations-of-spark-shuffle-spill-tp18202.html)
237. [Largest input data set observed for Spark.](http://apache-spark-user-list.1001560.n3.nabble.com/Largest-input-data-set-observed-for-Spark-tp2920.html)
238. [java.lang.StackOverflowError when calling count()](http://apache-spark-user-list.1001560.n3.nabble.com/java-lang-StackOverflowError-when-calling-count-tp5649.html)
239. [java.lang.OutOfMemoryError while running SVD MLLib example](http://apache-spark-user-list.1001560.n3.nabble.com/java-lang-OutOfMemoryError-while-running-SVD-MLLib-example-tp14972.html)

## Issues found by searching "Out of Memory" in Spark devloper mailing list

1. [Sorting partitions in Java](http://apache-spark-developers-list.1001551.n3.nabble.com/Sorting-partitions-in-Java-tp6715.html)
2. [Memory config issues](http://apache-spark-developers-list.1001551.n3.nabble.com/Memory-config-issues-tp10183.html)
3. [Fwd: Accumulator question](http://apache-spark-developers-list.1001551.n3.nabble.com/Fwd-Accumulator-question-tp8709.html)
4. [OOM when making bins in BinaryClassificationMetrics ?](http://apache-spark-developers-list.1001551.n3.nabble.com/OOM-when-making-bins-in-BinaryClassificationMetrics-tp9061.html)
5. [Storage of RDDs created via sc.parallelize](http://apache-spark-developers-list.1001551.n3.nabble.com/Storage-of-RDDs-created-via-sc-parallelize-tp11135.html)
6. [[GitHub] incubator-spark pull request: MLLIB-25: Implicit ALS runs out of m...](http://apache-spark-developers-list.1001551.n3.nabble.com/GitHub-incubator-spark-pull-request-MLLIB-25-Implicit-ALS-runs-out-of-m-tp2404.html)
7. [[GitHub] spark pull request: [WIP] [SPARK-1132] Persisting Web UI through r...](http://apache-spark-developers-list.1001551.n3.nabble.com/GitHub-spark-pull-request-WIP-SPARK-1132-Persisting-Web-UI-through-r-tp3173.html)
8. [Maximum size of vector that reduce can handle](http://apache-spark-developers-list.1001551.n3.nabble.com/Maximum-size-of-vector-that-reduce-can-handle-tp10256.html)
9. [[Graphx] some problem about using SVDPlusPlus](http://apache-spark-developers-list.1001551.n3.nabble.com/Graphx-some-problem-about-using-SVDPlusPlus-tp7896.html)
10. [TorrentBroadcast slow performance](http://apache-spark-developers-list.1001551.n3.nabble.com/TorrentBroadcast-slow-performance-tp8669.html)
11. [sparkSQL thread safe?](http://apache-spark-developers-list.1001551.n3.nabble.com/sparkSQL-thread-safe-tp7263.html)
12. [Low Level Kafka Consumer for Spark](http://apache-spark-developers-list.1001551.n3.nabble.com/Low-Level-Kafka-Consumer-for-Spark-tp7644.html)
13. [MLlib - logistic regression with GD vs LBFGS, sparse vs dense benchmark result](http://apache-spark-developers-list.1001551.n3.nabble.com/MLlib-logistic-regression-with-GD-vs-LBFGS-sparse-vs-dense-benchmark-result-tp6386.html)
14. [Too big data Spark SQL on Hive table on version 1.0.2 has some strange output](http://apache-spark-developers-list.1001551.n3.nabble.com/Too-big-data-Spark-SQL-on-Hive-table-on-version-1-0-2-has-some-strange-output-tp8662.html)
15. [test suite results in OOME](http://apache-spark-developers-list.1001551.n3.nabble.com/test-suite-results-in-OOME-tp40.html)
16. [oome from large map output status](http://apache-spark-developers-list.1001551.n3.nabble.com/oome-from-large-map-output-status-tp1851.html)
17. [Troubleshooting JVM OOM during Spark Unit Tests](http://apache-spark-developers-list.1001551.n3.nabble.com/Troubleshooting-JVM-OOM-during-Spark-Unit-Tests-tp9480.html)
18. [Spark master OOMs with exception stack trace stored in JobProgressListener (SPARK-4906)](http://apache-spark-developers-list.1001551.n3.nabble.com/Spark-master-OOMs-with-exception-stack-trace-stored-in-JobProgressListener-SPARK-4906-tp9857.html)
19. [take() reads every partition if the first one is empty](http://apache-spark-developers-list.1001551.n3.nabble.com/take-reads-every-partition-if-the-first-one-is-empty-tp7956.html)
20. [spark 1.3 sbt build seems to be broken](http://apache-spark-developers-list.1001551.n3.nabble.com/spark-1-3-sbt-build-seems-to-be-broken-tp10491.html)
21. [OutOfMemoryError when running sbt/sbt test](http://apache-spark-developers-list.1001551.n3.nabble.com/OutOfMemoryError-when-running-sbt-sbt-test-tp8056.html)
22. [Using memory mapped file for shuffle](http://apache-spark-developers-list.1001551.n3.nabble.com/Using-memory-mapped-file-for-shuffle-tp11576.html)
23. [Eliminate copy while sending data : any Akka experts here ?](http://apache-spark-developers-list.1001551.n3.nabble.com/Eliminate-copy-while-sending-data-any-Akka-experts-here-tp7127.html)
24. [Streaming partitions to driver for use in .toLocalIterator](http://apache-spark-developers-list.1001551.n3.nabble.com/Streaming-partitions-to-driver-for-use-in-toLocalIterator-tp10664.html)
25. [Apache spark on 27gb wikipedia data](http://apache-spark-developers-list.1001551.n3.nabble.com/Apache-spark-on-27gb-wikipedia-data-tp6487.html)
26. [[ANNOUNCE] Spark 1.2.0 Release Preview Posted](http://apache-spark-developers-list.1001551.n3.nabble.com/ANNOUNCE-Spark-1-2-0-Release-Preview-Posted-tp9400.html)
27. [Tests failed after assembling the latest code from github](http://apache-spark-developers-list.1001551.n3.nabble.com/Tests-failed-after-assembling-the-latest-code-from-github-tp6315.html)
28. [bug using kryo as closure serializer](http://apache-spark-developers-list.1001551.n3.nabble.com/bug-using-kryo-as-closure-serializer-tp6473.html)
29. [[VOTE] Release Apache Spark 1.3.1](http://apache-spark-developers-list.1001551.n3.nabble.com/VOTE-Release-Apache-Spark-1-3-1-tp11399.html)
30. [[RESULT] [VOTE] Release Apache Spark 1.3.1](http://apache-spark-developers-list.1001551.n3.nabble.com/RESULT-VOTE-Release-Apache-Spark-1-3-1-tp11470.html)
31. [[GitHub] spark pull request: Patch for SPARK-942](http://apache-spark-developers-list.1001551.n3.nabble.com/GitHub-spark-pull-request-Patch-for-SPARK-942-tp3311.html)
32. [[GitHub] spark pull request: [SPARK-1186] : Enrich the Spark Shell to suppo...](http://apache-spark-developers-list.1001551.n3.nabble.com/GitHub-spark-pull-request-SPARK-1186-Enrich-the-Spark-Shell-to-suppo-tp4000.html)