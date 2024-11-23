# BrandSentimentAnalysisYoutube
Fetches the Youtube comments about a brand in a given timeframe and provides the sentiment of each comment using TweetNLP LLM from huggingface

This tool is developed in Databricks platform on the cluster with following config
Runtime : 14.3 LTS ML
3 Workers & 1 Driver Types :  Standard_E32ds_v5 (256 gb memory and 32 cores each)
Spark Config:
spark.sql.adaptive.skewJoin.enabled true
spark.sql.adaptive.coalescePartitions.enabled true
spark.databricks.optimizer.adaptive.enabled true
spark.databricks.adaptive.autoBroadcastJoinThreshold 30MB
spark.sql.shuffle.partitions 32


