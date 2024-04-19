## Data Ingestion



- **Kafka Tools**

  Publish-subscribe messaging rethought as a distributed commit log.

  - [kafkat](https://github.com/airbnb/kafkat) - Simplified command-line administration for Kafka brokers.
  - [kafkacat](https://github.com/edenhill/kafkacat) - Generic command line non-JVM Apache Kafka producer and consumer.
  - [pg-kafka](https://github.com/xstevens/pg_kafka) - A PostgreSQL extension to produce messages to Apache Kafka.
  - [librdkafka](https://github.com/edenhill/librdkafka) - The Apache Kafka C/C++ library.
  - [kafka-docker](https://github.com/wurstmeister/kafka-docker) - Kafka in Docker.
  - [kafka-manager](https://github.com/yahoo/kafka-manager) - A tool for managing Apache Kafka.
  - [kafka-node](https://github.com/SOHU-Co/kafka-node) - Node.js client for Apache Kafka 0.8.
  - [Secor](https://github.com/pinterest/secor) - Pinterest's Kafka to S3 distributed consumer.
  - [Kafka-logger](https://github.com/uber/kafka-logger) - Kafka-winston logger for Node.js from uber.

- [AWS Kinesis](https://aws.amazon.com/kinesis/) - A fully managed, cloud-based service for real-time data processing over large, distributed data streams.

- [RabbitMQ](https://www.rabbitmq.com/) - Robust messaging for applications.

- [dlt](https://www.dlthub.com/) - A fast&simple pipeline building library for python data devs, runs in notebooks, cloud functions, airflow, etc.

- [FluentD](https://www.fluentd.org/) - An open source data collector for unified logging layer.

- [Embulk](https://www.embulk.org/) - An open source bulk data loader that helps data transfer between various databases, storages, file formats, and cloud services.

- [Apache Sqoop](https://sqoop.apache.org/) - A tool designed for efficiently transferring bulk data between Apache Hadoop and structured datastores such as relational databases.

- [Heka](https://github.com/mozilla-services/heka) - Data Acquisition and Processing Made Easy. Deprecated.

- [Gobblin](https://github.com/apache/incubator-gobblin) - Universal data ingestion framework for Hadoop from Linkedin.

- [Nakadi](https://nakadi.io/) - Nakadi is an open source event messaging platform that provides a REST API on top of Kafka-like queues.

- [Pravega](https://www.pravega.io/) - Pravega provides a new storage abstraction - a stream - for continuous and unbounded data.

- [Apache Pulsar](https://pulsar.apache.org/) - Apache Pulsar is an open-source distributed pub-sub messaging system.

- [AWS Data Wranlger](https://github.com/awslabs/aws-data-wrangler) - Utility belt to handle data on AWS.

- [Airbyte](https://airbyte.io/) - Open-source data integration for modern data teams.

- [Sling](https://slingdata.io/) - Sling is CLI data integration tool specialized in moving data between databases, as well as storage systems.

## File System



- HDFS

   

  \- A distributed file system designed to run on commodity hardware.

  - [Snakebite](https://github.com/spotify/snakebite) - A pure python HDFS client.

- AWS S3

   

  \- Object storage built to retrieve any amount of data from anywhere.

  - [smart_open](https://github.com/RaRe-Technologies/smart_open) - Utils for streaming large files (S3, HDFS, gzip, bz2).

- [Alluxio](https://www.alluxio.org/) - Alluxio is a memory-centric distributed storage system enabling reliable data sharing at memory-speed across cluster frameworks, such as Spark and MapReduce.

- [CEPH](https://ceph.com/) - Ceph is a unified, distributed storage system designed for excellent performance, reliability and scalability.

- [OrangeFS](https://www.orangefs.org/) - Orange File System is a branch of the Parallel Virtual File System.

- [SnackFS](https://github.com/tuplejump/snackfs-release) - SnackFS is our bite-sized, lightweight HDFS compatible FileSystem built over Cassandra.

- [GlusterFS](https://www.gluster.org/) - Gluster Filesystem.

- [XtreemFS](https://www.xtreemfs.org/) - Fault-tolerant distributed file system for all storage needs.

- [SeaweedFS](https://github.com/chrislusf/seaweedfs) - Seaweed-FS is a simple and highly scalable distributed file system. There are two objectives: to store billions of files! to serve the files fast! Instead of supporting full POSIX file system semantics, Seaweed-FS choose to implement only a key~file mapping. Similar to the word "NoSQL", you can call it as "NoFS".

- [S3QL](https://github.com/s3ql/s3ql/) - S3QL is a file system that stores all its data online using storage services like Google Storage, Amazon S3, or OpenStack.

- [LizardFS](https://lizardfs.com/) - LizardFS Software Defined Storage is a distributed, parallel, scalable, fault-tolerant, Geo-Redundant and highly available file system.

## Serialization format



- [Apache Avro](https://avro.apache.org/) - Apache Avro™ is a data serialization system.

- Apache Parquet

   

  \- Apache Parquet is a columnar storage format available to any project in the Hadoop ecosystem, regardless of the choice of data processing framework, data model or programming language.

  - [Snappy](https://github.com/google/snappy) - A fast compressor/decompressor. Used with Parquet.
  - [PigZ](https://zlib.net/pigz/) - A parallel implementation of gzip for modern multi-processor, multi-core machines.

- [Apache ORC](https://orc.apache.org/) - The smallest, fastest columnar storage for Hadoop workloads.

- [Apache Thrift](https://thrift.apache.org/) - The Apache Thrift software framework, for scalable cross-language services development.

- [ProtoBuf](https://github.com/protocolbuffers/protobuf) - Protocol Buffers - Google's data interchange format.

- [SequenceFile](https://wiki.apache.org/hadoop/SequenceFile) - SequenceFile is a flat file consisting of binary key/value pairs. It is extensively used in MapReduce as input/output formats.

- [Kryo](https://github.com/EsotericSoftware/kryo) - Kryo is a fast and efficient object graph serialization framework for Java.

## Stream Processing



- [Apache Beam](https://beam.apache.org/) - Apache Beam is a unified programming model that implements both batch and streaming data processing jobs that run on many execution engines.

- [Spark Streaming](https://spark.apache.org/streaming/) - Spark Streaming makes it easy to build scalable fault-tolerant streaming applications.

- [Apache Flink](https://flink.apache.org/) - Apache Flink is a streaming dataflow engine that provides data distribution, communication, and fault tolerance for distributed computations over data streams.

- [Apache Storm](https://storm.apache.org/) - Apache Storm is a free and open source distributed realtime computation system.

- [Apache Samza](https://samza.apache.org/) - Apache Samza is a distributed stream processing framework.

- [Apache NiFi](https://nifi.apache.org/) - An easy to use, powerful, and reliable system to process and distribute data.

- [Apache Hudi](https://hudi.apache.org/) - An open source framework for managing storage for real time processing, one of the most interesting feature is the Upsert.

- [VoltDB](https://voltdb.com/) - VoltDb is an ACID-compliant RDBMS which uses a [shared nothing architecture](https://en.wikipedia.org/wiki/Shared-nothing_architecture).

- [PipelineDB](https://github.com/pipelinedb/pipelinedb) - The Streaming SQL Database.

- [Spring Cloud Dataflow](https://cloud.spring.io/spring-cloud-dataflow/) - Streaming and tasks execution between Spring Boot apps.

- [Bonobo](https://www.bonobo-project.org/) - Bonobo is a data-processing toolkit for python 3.5+.

- [Robinhood's Faust](https://github.com/faust-streaming/faust) - Forever scalable event processing & in-memory durable K/V store as a library with asyncio & static typing.

- [HStreamDB](https://github.com/hstreamdb/hstream) - The streaming database built for IoT data storage and real-time processing.

- [Kuiper](https://github.com/emqx/kuiper) - An edge lightweight IoT data analytics/streaming software implemented by Golang, and it can be run at all kinds of resource-constrained edge devices.

- [Zilla](https://github.com/aklivity/zilla) - - An API gateway built for event-driven architectures and streaming that supports standard protocols such as HTTP, SSE, gRPC, MQTT and the native Kafka protocol.

- RisingWave

- Streaamsets

  

## Batch Processing



- [Hadoop MapReduce](https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) - Hadoop MapReduce is a software framework for easily writing applications which process vast amounts of data (multi-terabyte data-sets) - in-parallel on large clusters (thousands of nodes) - of commodity hardware in a reliable, fault-tolerant manner.

- [Spark](https://spark.apache.org/) - A multi-language engine for executing data engineering, data science, and machine learning on single-node machines or clusters.

  - [Spark Packages](https://spark-packages.org/) - A community index of packages for Apache Spark.
  - [Deep Spark](https://github.com/Stratio/deep-spark) - Connecting Apache Spark with different data stores. Deprecated.
  - [Spark RDD API Examples](https://homepage.cs.latrobe.edu.au/zhe/ZhenHeSparkRDDAPIExamples.html) - Examples by Zhen He.
  - [Livy](https://livy.incubator.apache.org/) - The REST Spark Server.
  - [Delight](https://github.com/datamechanics/delight) - A free & cross platform monitoring tool (Spark UI / Spark History Server alternative).

- [AWS EMR](https://aws.amazon.com/emr/) - A web service that makes it easy to quickly and cost-effectively process vast amounts of data.

- [Data Mechanics](https://www.datamechanics.co/) - A cloud-based platform deployed on Kubernetes making Apache Spark more developer-friendly and cost-effective.

- [Tez](https://tez.apache.org/) - An application framework which allows for a complex directed-acyclic-graph of tasks for processing data.

- [Bistro](https://github.com/asavinov/bistro) - A light-weight engine for general-purpose data processing including both batch and stream analytics. It is based on a novel unique data model, which represents data via *functions* and processes data via *columns operations* as opposed to having only set operations in conventional approaches like MapReduce or SQL.

- Batch ML

  - [H2O](https://www.h2o.ai/) - Fast scalable machine learning API for smarter applications.
  - [Mahout](https://mahout.apache.org/) - An environment for quickly creating scalable performant machine learning applications.
  - [Spark MLlib](https://spark.apache.org/docs/latest/ml-guide.html) - Spark's scalable machine learning library consisting of common learning algorithms and utilities, including classification, regression, clustering, collaborative filtering, dimensionality reduction, as well as underlying optimization primitives.

- Batch Graph

  - [GraphLab Create](https://turi.com/products/create/docs/) - A machine learning platform that enables data scientists and app developers to easily create intelligent apps at scale.
  - [Giraph](https://giraph.apache.org/) - An iterative graph processing system built for high scalability.
  - [Spark GraphX](https://spark.apache.org/graphx/) - Apache Spark's API for graphs and graph-parallel computation.

- Batch SQL

  - [Presto](https://prestodb.github.io/docs/current/index.html) - A distributed SQL query engine designed to query large data sets distributed over one or more heterogeneous data sources.

  - Hive

     

    \- Data warehouse software facilitates querying and managing large datasets residing in distributed storage.

    - [Hivemall](https://github.com/apache/incubator-hivemall) - Scalable machine learning library for Hive/Hadoop.
    - [PyHive](https://github.com/dropbox/PyHive) - Python interface to Hive and Presto.

  - [Drill](https://drill.apache.org/) - Schema-free SQL Query Engine for Hadoop, NoSQL and Cloud Storage.

## Charts and Dashboards



- [Highcharts](https://www.highcharts.com/) - A charting library written in pure JavaScript, offering an easy way of adding interactive charts to your web site or web application.

- [ZingChart](https://www.zingchart.com/) - Fast JavaScript charts for any data set.

- [C3.js](https://c3js.org/) - D3-based reusable chart library.

- D3.js

   

  \- A JavaScript library for manipulating documents based on data.

  - [D3Plus](https://d3plus.org/) - D3's simplier, easier to use cousin. Mostly predefined templates that you can just plug data in.

- [SmoothieCharts](https://smoothiecharts.org/) - A JavaScript Charting Library for Streaming Data.

- [PyXley](https://github.com/stitchfix/pyxley) - Python helpers for building dashboards using Flask and React.

- [Plotly](https://github.com/plotly/dash) - Flask, JS, and CSS boilerplate for interactive, web-based visualization apps in Python.

- [Apache Superset](https://github.com/apache/incubator-superset) - Apache Superset (incubating) - A modern, enterprise-ready business intelligence web application.

- [Redash](https://redash.io/) - Make Your Company Data Driven. Connect to any data source, easily visualize and share your data.

- [Metabase](https://github.com/metabase/metabase) - Metabase is the easy, open source way for everyone in your company to ask questions and learn from data.

- [PyQtGraph](https://www.pyqtgraph.org/) - PyQtGraph is a pure-python graphics and GUI library built on PyQt4 / PySide and numpy. It is intended for use in mathematics / scientific / engineering applications.

## Workflow



- Luigi

   

  \- Luigi is a Python module that helps you build complex pipelines of batch jobs.

  - [CronQ](https://github.com/seatgeek/cronq) - An application cron-like system. [Used](https://chairnerd.seatgeek.com/building-out-the-seatgeek-data-pipeline/) w/Luige. Deprecated.

- [Cascading](https://www.cascading.org/) - Java based application development platform.

- [Airflow](https://github.com/apache/airflow) - Airflow is a system to programmaticaly author, schedule and monitor data pipelines.

- [Azkaban](https://azkaban.github.io/) - Azkaban is a batch workflow job scheduler created at LinkedIn to run Hadoop jobs. Azkaban resolves the ordering through job dependencies and provides an easy to use web user interface to maintain and track your workflows.

- [Oozie](https://oozie.apache.org/) - Oozie is a workflow scheduler system to manage Apache Hadoop jobs.

- [Pinball](https://github.com/pinterest/pinball) - DAG based workflow manager. Job flows are defined programmaticaly in Python. Support output passing between jobs.

- [Dagster](https://github.com/dagster-io/dagster) - Dagster is an open-source Python library for building data applications.

- [Kedro](https://kedro.readthedocs.io/en/latest/) - Kedro is a framework that makes it easy to build robust and scalable data pipelines by providing uniform project templates, data abstraction, configuration and pipeline assembly.

- [Dataform](https://dataform.co/) - An open-source framework and web based IDE to manage datasets and their dependencies. SQLX extends your existing SQL warehouse dialect to add features that support dependency management, testing, documentation and more.

- [Census](https://getcensus.com/) - A reverse-ETL tool that let you sync data from your cloud data warehouse to SaaS applications like Salesforce, Marketo, HubSpot, Zendesk, etc. No engineering favors required—just SQL.

- [dbt](https://getdbt.com/) - A command line tool that enables data analysts and engineers to transform data in their warehouses more effectively.

- [RudderStack](https://github.com/rudderlabs/rudder-server) - A warehouse-first Customer Data Platform that enables you to collect data from every application, website and SaaS platform, and then activate it in your warehouse and business tools.

- [PACE](https://github.com/getstrm/pace) - An open source framework that allows you to enforce agreements on how data should be accessed, used, and transformed, regardless of the data platform (Snowflake, BigQuery, DataBricks, etc.)

- [Prefect](https://prefect.io/) - Prefect is an orchestration and observability platform. With it, developers can rapidly build and scale resilient code, and triage disruptions effortlessly.

- [Multiwoven](https://github.com/Multiwoven/multiwoven) - The open-source reverse ETL, data activation platform for modern data teams.

- [SuprSend](https://www.suprsend.com/products/workflows) - Create automated workflows and logic using API's for your notification service. Add templates, batching, preferences, inapp inbox with workflows to trigger notifications directly from your data warehouse.

- [MageAI](https://mage.ai/)

  - Practical Samples
    - [Mage Community Samples](https://mage.ai/)
    - [filthy job stalker](https://github.com/kirilscherbach/animated-broccoli)



#### ML Flows

- https://flyte.org/

## Data Lake Management



- [lakeFS](https://github.com/treeverse/lakeFS) - lakeFS is an open source platform that delivers resilience and manageability to object-storage based data lakes.
- [Project Nessie](https://github.com/projectnessie/nessie) - Project Nessie is a Transactional Catalog for Data Lakes with Git-like semantics. Works with Apache Iceberg tables.

## ELK Elastic Logstash Kibana



- [docker-logstash](https://github.com/pblittle/docker-logstash) - A highly configurable logstash (1.4.4) - docker image running Elasticsearch (1.7.0) - and Kibana (3.1.2).
- [elasticsearch-jdbc](https://github.com/jprante/elasticsearch-jdbc) - JDBC importer for Elasticsearch.
- [ZomboDB](https://github.com/zombodb/zombodb) - Postgres Extension that allows creating an index backed by Elasticsearch.

## Docker



- [Gockerize](https://github.com/redbooth/gockerize) - Package golang service into minimal docker containers.
- [Flocker](https://github.com/ClusterHQ/flocker) - Easily manage Docker containers & their data.
- [Rancher](https://rancher.com/rancher-os/) - RancherOS is a 20mb Linux distro that runs the entire OS as Docker containers.
- [Kontena](https://www.kontena.io/) - Application Containers for Masses.
- [Weave](https://github.com/weaveworks/weave) - Weaving Docker containers into applications.
- [Zodiac](https://github.com/CenturyLinkLabs/zodiac) - A lightweight tool for easy deployment and rollback of dockerized applications.
- [cAdvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers.
- [Micro S3 persistence](https://github.com/figadore/micro-s3-persistence) - Docker microservice for saving/restoring volume data to S3.
- [Rocker-compose](https://github.com/grammarly/rocker-compose) - Docker composition tool with idempotency features for deploying apps composed of multiple containers. Deprecated.
- [Nomad](https://github.com/hashicorp/nomad) - Nomad is a cluster manager, designed for both long lived services and short lived batch processing workloads.
- [ImageLayers](https://imagelayers.io/) - Vizualize docker images and the layers that compose them.

## Datasets



### Realtime



- [Twitter Realtime](https://developer.twitter.com/en/docs/tweets/filter-realtime/overview) - The Streaming APIs give developers low latency access to Twitter's global stream of Tweet data.
- [Eventsim](https://github.com/Interana/eventsim) - Event data simulator. Generates a stream of pseudo-random events from a set of users, designed to simulate web traffic.
- [Reddit](https://www.reddit.com/r/datasets/comments/3mk1vg/realtime_data_is_available_including_comments/) - Real-time data is available including comments, submissions and links posted to reddit.

### Data Dumps



- [GitHub Archive](https://www.gharchive.org/) - GitHub's public timeline since 2011, updated every hour.
- [Common Crawl](https://commoncrawl.org/) - Open source repository of web crawl data.
- [Wikipedia](https://dumps.wikimedia.org/enwiki/latest/) - Wikipedia's complete copy of all wikis, in the form of wikitext source and metadata embedded in XML. A number of raw database tables in SQL form are also available.

## Monitoring



### Prometheus



- [Prometheus.io](https://github.com/prometheus/prometheus) - An open-source service monitoring system and time series database.
- [HAProxy Exporter](https://github.com/prometheus/haproxy_exporter) - Simple server that scrapes HAProxy stats and exports them via HTTP for Prometheus consumption.

## Profiling



### Data Profiler



- [Data Profiler](https://github.com/capitalone/dataprofiler) - The DataProfiler is a Python library designed to make data analysis, monitoring, and sensitive data detection easy.

## Testing



- [Grai](https://github.com/grai-io/grai-core/) - A data catalog tool that integrates into your CI system exposing downstream impact testing of data changes. These tests prevent data changes which might break data pipelines or BI dashboards from making it to production.
- [DQOps](https://github.com/dqops/dqo) - An open-source data quality platform for the whole data platform lifecycle from profiling new data sources to applying full automation of data quality monitoring.



- Orchestration
  - [Mage](https://www.mage.ai/)
  - [Astronomer](https://www.astronomer.io/)
  - [Prefect](https://www.prefect.io/)
  - [Dagster](https://www.dagster.io/)
  - [Airbyte](https://airbyte.com/)
  - [Shipyard](https://www.shipyardapp.com/)
  - [Hamilton](https://github.com/dagworks-inc/hamilton)
- Data Lake / Cloud
  - [Tabular](https://www.tabular.io/)
  - [Microsoft](https://www.microsoft.com/)
  - [Databricks](https://www.databricks.com/company/about-us)
  - [Onehouse](https://www.onehouse.ai/)
  - [Delta Lake](https://delta.io/)
- Data Warehouse
  - [Snowflake](https://www.snowflake.com/en/)
  - [Firebolt](https://www.firebolt.io/)
- Data Quality
  - [dbt](https://www.getdbt.com/)
  - [Gable](https://www.gable.ai/)
  - [Great Expectations](https://www.greatexpectations.io/)
  - [Streamdal](https://streamdal.com/)
  - [Coalesce](https://coalesce.io/)
  - [Soda](https://www.soda.io/)
  - [DQOps](https://dqops.com/)
- Education Companies
  - [DataExpert.io](https://www.dataexpert.io/)
  - [LearnDataEngineering.com](https://www.learndataengineering.com/)
  - [AlgoExpert](https://www.algoexpert.io/)
  - [ByteByteGo](https://www.bytebytego.com/)
- Analytics / Visualization
  - [Preset](https://www.preset.io/)
  - [Starburst](https://www.starburst.io/)
  - [Metabase](https://www.metabase.com/)
- Data Integration
  - [Cube](https://cube.dev/)
  - [Fivetran](https://www.fivetran.com/)
  - [Airbyte](https://airbyte.io/)
  - [dlt](https://dlthub.com/)
  - [Sling](https://slingdata.io/)
- Modern OLAP
  - [Apache Druid](https://druid.apache.org/)
  - [ClickHouse](https://clickhouse.com/)
  - [Apache Pinot](https://pinot.apache.org/)
  - [Apache Kylin](https://kylin.apache.org/)