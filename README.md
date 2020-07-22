# Introduction to Amazon EMR

Amazon EMR is the industry leading cloud-native big data platform for processing vast amounts of data quickly and cost-effectively at scale. Using open source tools such as Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi (Incubating), and Presto, coupled with the dynamic scalability of Amazon EC2 and scalable storage of Amazon S3, EMR gives analytical teams the engines and elasticity to run Petabyte-scale analysis for a fraction of the cost of traditional on-premises clusters. EMR gives teams the flexibility to run use cases on single-purpose, short lived clusters that automatically scale to meet demand, or on long running highly available clusters using the new multi-master deployment mode.

Learn more about Amazon EMR [here](https://aws.amazon.com/emr/).

# Apache Hudi

Apache Hudi is an open-source data management framework used to simplify incremental data processing and data pipeline development. Apache Hudi enables you to manage data at the record-level in Amazon S3 to simplify Change Data Capture (CDC) and streaming data ingestion, and provides a framework to handle data privacy use cases requiring record level updates and deletes. Data sets managed by Apache Hudi are stored in S3 using open storage formats, and integrations with Presto, Apache Hive, Apache Spark, and AWS Glue Data Catalog give you near real-time access to updated data using familiar tools.

Hudi is integrated with Apache Spark, Apache Hive, and Presto. With Amazon EMR release version 5.28.0 and later, Amazon EMR installs Hudi components by default when Spark, Hive, or Presto are installed. You can use Spark or the Hudi DeltaStreamer utility to create or update Hudi datasets. You can use Hive, Spark, or Presto to query a Hudi dataset interactively or build data processing pipelines using incremental pull. Incremental pull refers to the ability to pull only the data that changed between two actions.

Learn more about Apache Hudi [here](https://docs.aws.amazon.com/emr/latest/ReleaseGuide/emr-hudi.html).


## Labs
|Part |Lab Name |Lab Description |
|---- |---- | ----|
|1 |[1a - Getting Started](L1a-StartHere.md) |Connect to the AWS Management Console |
| |[1b - Cloud9](L1b-Cloud9.md) |Create the Cloud9 Environment |
| |[1c - EMR](L1c-EMRCreate.md) |Create the EMR Cluster |
|2 |[2a - EMR Notebooks](L2a-Notebook.md) |Create EMR Notebooks/Jupyter |





