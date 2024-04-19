## Databases



- Relational

  - [RQLite](https://github.com/rqlite/rqlite) - Replicated SQLite using the Raft consensus protocol.

  - MySQL

     

    \- The world's most popular open source database.

    - [TiDB](https://github.com/pingcap/tidb) - TiDB is a distributed NewSQL database compatible with MySQL protocol.
    - [Percona XtraBackup](https://www.percona.com/software/mysql-database/percona-xtrabackup) - Percona XtraBackup is a free, open source, complete online backup solution for all versions of Percona Server, MySQL® and MariaDB®.
    - [mysql_utils](https://github.com/pinterest/mysql_utils) - Pinterest MySQL Management Tools.

  - [MariaDB](https://mariadb.org/) - An enhanced, drop-in replacement for MySQL.

  - [PostgreSQL](https://www.postgresql.org/) - The world's most advanced open source database.

  - [Amazon RDS](https://aws.amazon.com/rds/) - Amazon RDS makes it easy to set up, operate, and scale a relational database in the cloud.

  - [Crate.IO](https://crate.io/) - Scalable SQL database with the NOSQL goodies.

- Key-Value

  - [Redis](https://redis.io/) - An open source, BSD licensed, advanced key-value cache and store.
  - [Riak](https://docs.basho.com/riak/kv/) - A distributed database designed to deliver maximum data availability by distributing data across multiple servers.
  - [AWS DynamoDB](https://aws.amazon.com/dynamodb/) - A fast and flexible NoSQL database service for all applications that need consistent, single-digit millisecond latency at any scale.
  - [HyperDex](https://github.com/rescrv/HyperDex) - HyperDex is a scalable, searchable key-value store. Deprecated.
  - [SSDB](https://ssdb.io/) - A high performance NoSQL database supporting many data structures, an alternative to Redis.
  - [Kyoto Tycoon](https://github.com/alticelabs/kyoto) - Kyoto Tycoon is a lightweight network server on top of the Kyoto Cabinet key-value database, built for high-performance and concurrency.
  - [IonDB](https://github.com/iondbproject/iondb) - A key-value store for microcontroller and IoT applications.

- Column

  - Cassandra

     

    \- The right choice when you need scalability and high availability without compromising performance.

    - [Cassandra Calculator](https://www.ecyrd.com/cassandracalculator/) - This simple form allows you to try out different values for your Apache Cassandra cluster and see what the impact is for your application.
    - [CCM](https://github.com/pcmanus/ccm) - A script to easily create and destroy an Apache Cassandra cluster on localhost.
    - [ScyllaDB](https://github.com/scylladb/scylla) - NoSQL data store using the seastar framework, compatible with Apache Cassandra.

  - [HBase](https://hbase.apache.org/) - The Hadoop database, a distributed, scalable, big data store.

  - [AWS Redshift](https://aws.amazon.com/redshift/) - A fast, fully managed, petabyte-scale data warehouse that makes it simple and cost-effective to analyze all your data using your existing business intelligence tools.

  - [FiloDB](https://github.com/filodb/FiloDB) - Distributed. Columnar. Versioned. Streaming. SQL.

  - [Vertica](https://www.vertica.com/) - Distributed, MPP columnar database with extensive analytics SQL.

  - [ClickHouse](https://clickhouse.tech/) - Distributed columnar DBMS for OLAP. SQL.

- Document

  - MongoDB

     

    \- An open-source, document database designed for ease of development and scaling.

    - [Percona Server for MongoDB](https://www.percona.com/software/mongo-database/percona-server-for-mongodb) - Percona Server for MongoDB® is a free, enhanced, fully compatible, open source, drop-in replacement for the MongoDB® Community Edition that includes enterprise-grade features and functionality.
    - [MemDB](https://github.com/rain1017/memdb) - Distributed Transactional In-Memory Database (based on MongoDB).

  - [Elasticsearch](https://www.elastic.co/) - Search & Analyze Data in Real Time.

  - [Couchbase](https://www.couchbase.com/) - The highest performing NoSQL distributed database.

  - [RethinkDB](https://rethinkdb.com/) - The open-source database for the realtime web.

  - [RavenDB](https://ravendb.net/) - Fully Transactional NoSQL Document Database.

- Graph

  - [Neo4j](https://neo4j.com/) - The world's leading graph database.
  - [OrientDB](https://orientdb.com/) - 2nd Generation Distributed Graph Database with the flexibility of Documents in one product with an Open Source commercial friendly license.
  - [ArangoDB](https://www.arangodb.com/) - A distributed free and open-source database with a flexible data model for documents, graphs, and key-values.
  - [Titan](https://titan.thinkaurelius.com/) - A scalable graph database optimized for storing and querying graphs containing hundreds of billions of vertices and edges distributed across a multi-machine cluster.
  - [FlockDB](https://github.com/twitter-archive/flockdb) - A distributed, fault-tolerant graph database by Twitter. Deprecated.

- Distributed

  - [DAtomic](https://www.datomic.com/) - The fully transactional, cloud-ready, distributed database.
  - [Apache Geode](https://geode.apache.org/) - An open source, distributed, in-memory database for scale-out applications.
  - [Gaffer](https://github.com/gchq/Gaffer) - A large-scale graph database.

- Timeseries

  - [InfluxDB](https://github.com/influxdata/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
  - [OpenTSDB](https://github.com/OpenTSDB/opentsdb) - A scalable, distributed Time Series Database.
  - [QuestDB](https://questdb.io/) - A relational column-oriented database designed for real-time analytics on time series and event data.
  - [kairosdb](https://github.com/kairosdb/kairosdb) - Fast scalable time series database.
  - [Heroic](https://github.com/spotify/heroic) - A scalable time series database based on Cassandra and Elasticsearch, by Spotify.
  - [Druid](https://github.com/apache/incubator-druid) - Column oriented distributed data store ideal for powering interactive applications.
  - [Riak-TS](https://basho.com/products/riak-ts/) - Riak TS is the only enterprise-grade NoSQL time series database optimized specifically for IoT and Time Series data.
  - [Akumuli](https://github.com/akumuli/Akumuli) - Akumuli is a numeric time-series database. It can be used to capture, store and process time-series data in real-time. The word "akumuli" can be translated from esperanto as "accumulate".
  - [Rhombus](https://github.com/Pardot/Rhombus) - A time-series object store for Cassandra that handles all the complexity of building wide row indexes.
  - [Dalmatiner DB](https://github.com/dalmatinerdb/dalmatinerdb) - Fast distributed metrics database.
  - [Blueflood](https://github.com/rackerlabs/blueflood) - A distributed system designed to ingest and process time series data.
  - [Timely](https://github.com/NationalSecurityAgency/timely) - Timely is a time series database application that provides secure access to time series data based on Accumulo and Grafana.

- Other

  - [Tarantool](https://github.com/tarantool/tarantool/) - Tarantool is an in-memory database and application server.
  - [GreenPlum](https://github.com/greenplum-db/gpdb) - The Greenplum Database (GPDB) - An advanced, fully featured, open source data warehouse. It provides powerful and rapid analytics on petabyte scale data volumes.
  - [cayley](https://github.com/cayleygraph/cayley) - An open-source graph database. Google.
  - [Snappydata](https://github.com/SnappyDataInc/snappydata) - SnappyData: OLTP + OLAP Database built on Apache Spark.
  - [TimescaleDB](https://www.timescale.com/) - Built as an extension on top of PostgreSQL, TimescaleDB is a time-series SQL database providing fast analytics, scalability, with automated data management on a proven storage engine.

- Vector Databases & AI 

  - https://github.com/mindsdb/mindsdb
  - 