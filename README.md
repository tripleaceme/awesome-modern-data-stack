# Awesome Modern Data Stack

A curated list of open-source tools covering every layer of the modern data stack — from ingestion to visualization.

---

## Data Ingestion / ELT

| Tool | Description | GitHub |
|------|-------------|--------|
| **Airbyte** | ELT data integration platform, 300+ connectors | [airbytehq/airbyte](https://github.com/airbytehq/airbyte) |
| **Meltano** | ELT for the DataOps era (Singer-based) | [meltano/meltano](https://github.com/meltano/meltano) |
| **Singer** | Simple, composable ETL (taps & targets) | [singer-io/getting-started](https://github.com/singer-io/getting-started) |
| **Sling** | Fast data movement CLI (DB-to-DB, file-to-DB) | [slingdata-io/sling-cli](https://github.com/slingdata-io/sling-cli) |
| **CloudQuery** | High-performance ELT framework (Go, plugin-based) | [cloudquery/cloudquery](https://github.com/cloudquery/cloudquery) |
| **Ingestr** | CLI to copy data between any source and destination | [bruin-data/ingestr](https://github.com/bruin-data/ingestr) |
| **OLake** | CDC and batch replication from databases and Kafka into Apache Iceberg (Go) | [datazip-inc/olake](https://github.com/datazip-inc/olake) |

## Data Warehousing / OLAP / Query Engines

| Tool | Description | GitHub |
|------|-------------|--------|
| **Apache Hive** | SQL-on-Hadoop data warehouse | [apache/hive](https://github.com/apache/hive) |
| **ClickHouse** | Column-oriented OLAP database | [ClickHouse/ClickHouse](https://github.com/ClickHouse/ClickHouse) |
| **Apache Druid** | Real-time analytics database | [apache/druid](https://github.com/apache/druid) |
| **DuckDB** | In-process analytical database | [duckdb/duckdb](https://github.com/duckdb/duckdb) |
| **Apache Doris** | Real-time analytical database | [apache/doris](https://github.com/apache/doris) |
| **StarRocks** | High-performance analytical database | [StarRocks/starrocks](https://github.com/StarRocks/starrocks) |
| **Apache Pinot** | Real-time distributed OLAP | [apache/pinot](https://github.com/apache/pinot) |
| **Trino** | Distributed SQL query engine (formerly Presto SQL) | [trinodb/trino](https://github.com/trinodb/trino) |
| **Apache DataFusion** | Rust-based query engine | [apache/datafusion](https://github.com/apache/datafusion) |

## Data Lake / Lakehouse / Table Formats

| Tool | Description | GitHub |
|------|-------------|--------|
| **Apache Iceberg** | Open table format for huge analytics datasets | [apache/iceberg](https://github.com/apache/iceberg) |
| **Delta Lake** | Storage layer with ACID on data lakes | [delta-io/delta](https://github.com/delta-io/delta) |
| **Apache Hudi** | Streaming data lake platform | [apache/hudi](https://github.com/apache/hudi) |
| **Apache Paimon** | Streaming data lake storage | [apache/paimon](https://github.com/apache/paimon) |
| **Nessie** | Git-like catalog for data lakes | [projectnessie/nessie](https://github.com/projectnessie/nessie) |
| **LakeFS** | Git-like version control for data lakes | [treeverse/lakeFS](https://github.com/treeverse/lakeFS) |

## Data Transformation

| Tool | Description | GitHub |
|------|-------------|--------|
| **dbt-core** | SQL-first transformation framework | [dbt-labs/dbt-core](https://github.com/dbt-labs/dbt-core) |
| **SQLMesh** | Data transformation framework (dbt alternative) | [TobikoData/sqlmesh](https://github.com/TobikoData/sqlmesh) |
| **SQLGlot** | SQL parser and transpiler (20+ dialects) | [tobymao/sqlglot](https://github.com/tobymao/sqlglot) |
| **Apache Spark** | Unified analytics engine | [apache/spark](https://github.com/apache/spark) |
| **Polars** | Lightning-fast DataFrame library (Rust) | [pola-rs/polars](https://github.com/pola-rs/polars) |
| **pandas** | Python data analysis library | [pandas-dev/pandas](https://github.com/pandas-dev/pandas) |

## Orchestration / Workflow

| Tool | Description | GitHub |
|------|-------------|--------|
| **Apache Airflow** | Workflow orchestration platform | [apache/airflow](https://github.com/apache/airflow) |
| **Dagster** | Data orchestrator for ML, analytics, and ETL | [dagster-io/dagster](https://github.com/dagster-io/dagster) |
| **Prefect** | Modern workflow orchestration | [PrefectHQ/prefect](https://github.com/PrefectHQ/prefect) |
| **Mage** | Pipeline tool for transforming and integrating data | [mage-ai/mage-ai](https://github.com/mage-ai/mage-ai) |
| **Kestra** | Event-driven orchestration (declarative YAML) | [kestra-io/kestra](https://github.com/kestra-io/kestra) |
| **Windmill** | Developer platform for scripts, workflows, and UIs | [windmill-labs/windmill](https://github.com/windmill-labs/windmill) |
| **Temporal** | Durable execution platform | [temporalio/temporal](https://github.com/temporalio/temporal) |

## Data Quality / Testing / Observability

| Tool | Description | GitHub |
|------|-------------|--------|
| **Great Expectations** | Data validation and profiling | [great-expectations/great_expectations](https://github.com/great-expectations/great_expectations) |
| **Soda Core** | Data quality checks in YAML | [sodadata/soda-core](https://github.com/sodadata/soda-core) |
| **Elementary** | dbt-native data observability | [elementary-data/elementary](https://github.com/elementary-data/elementary) |
| **data-diff** | Data diffing and regression testing | [datafold/data-diff](https://github.com/datafold/data-diff) |
| **dbt-expectations** | Great Expectations-style tests for dbt | [calogica/dbt-expectations](https://github.com/calogica/dbt-expectations) |
| **OpenMetadata** | Data quality and metadata platform | [open-metadata/OpenMetadata](https://github.com/open-metadata/OpenMetadata) |

## Data Catalog / Metadata / Governance

| Tool | Description | GitHub |
|------|-------------|--------|
| **OpenMetadata** | Unified metadata platform | [open-metadata/OpenMetadata](https://github.com/open-metadata/OpenMetadata) |
| **DataHub** | Metadata platform (LinkedIn) | [datahub-project/datahub](https://github.com/datahub-project/datahub) |
| **Apache Atlas** | Data governance and metadata | [apache/atlas](https://github.com/apache/atlas) |
| **Amundsen** | Data discovery and metadata (Lyft) | [amundsen-io/amundsen](https://github.com/amundsen-io/amundsen) |
| **Marquez** | Metadata service for data lineage | [MarquezProject/marquez](https://github.com/MarquezProject/marquez) |
| **OpenLineage** | Open standard for data lineage | [OpenLineage/OpenLineage](https://github.com/OpenLineage/OpenLineage) |

## Streaming / Real-Time

| Tool | Description | GitHub |
|------|-------------|--------|
| **Apache Kafka** | Distributed event streaming | [apache/kafka](https://github.com/apache/kafka) |
| **Apache Flink** | Stream and batch processing | [apache/flink](https://github.com/apache/flink) |
| **Redpanda** | Kafka-compatible streaming (C++) | [redpanda-data/redpanda](https://github.com/redpanda-data/redpanda) |
| **RisingWave** | Streaming database (Postgres-compatible) | [risingwavelabs/risingwave](https://github.com/risingwavelabs/risingwave) |
| **Apache Pulsar** | Distributed pub-sub messaging | [apache/pulsar](https://github.com/apache/pulsar) |
| **Redpanda Connect** | Stream processing made simple (formerly Benthos) | [redpanda-data/connect](https://github.com/redpanda-data/connect) |
| **Materialize** | Streaming SQL database | [MaterializeInc/materialize](https://github.com/MaterializeInc/materialize) |

## BI / Visualization / Analytics

| Tool | Description | GitHub |
|------|-------------|--------|
| **Apache Superset** | Data exploration and visualization | [apache/superset](https://github.com/apache/superset) |
| **Metabase** | Simple, powerful BI for everyone | [metabase/metabase](https://github.com/metabase/metabase) |
| **Redash** | Connect to any data source, visualize | [getredash/redash](https://github.com/getredash/redash) |
| **Lightdash** | dbt-powered BI | [lightdash/lightdash](https://github.com/lightdash/lightdash) |
| **Evidence** | Code-driven BI (Markdown + SQL) | [evidence-dev/evidence](https://github.com/evidence-dev/evidence) |
| **Grafana** | Observability dashboards | [grafana/grafana](https://github.com/grafana/grafana) |
| **Rill** | Fast dashboards from data lakes | [rilldata/rill](https://github.com/rilldata/rill) |

## Reverse ETL / Data Activation

| Tool | Description | GitHub |
|------|-------------|--------|
| **Multiwoven** | Open-source reverse ETL | [Multiwoven/multiwoven](https://github.com/Multiwoven/multiwoven) |
| **Polytomic** | Reverse ETL platform | [polytomic/polytomic](https://github.com/polytomic/polytomic) |
| **Grouparoo** | Reverse ETL (archived) | [grouparoo/grouparoo](https://github.com/grouparoo/grouparoo) |

## Feature Store / ML Data

| Tool | Description | GitHub |
|------|-------------|--------|
| **Feast** | Feature store for ML | [feast-dev/feast](https://github.com/feast-dev/feast) |
| **Hopsworks** | Data platform for ML with feature store | [logicalclocks/hopsworks](https://github.com/logicalclocks/hopsworks) |

## Semantic Layer

| Tool | Description | GitHub |
|------|-------------|--------|
| **Cube** | Headless BI / semantic layer | [cube-js/cube](https://github.com/cube-js/cube) |
| **MetriQL** | Metric store as code | [metriql/metriql](https://github.com/metriql/metriql) |

## Data Privacy / Access Control

| Tool | Description | GitHub |
|------|-------------|--------|
| **Apache Ranger** | Authorization and auditing | [apache/ranger](https://github.com/apache/ranger) |
| **Open Policy Agent** | General-purpose policy engine | [open-policy-agent/opa](https://github.com/open-policy-agent/opa) |

## Notebooks / Exploration

| Tool | Description | GitHub |
|------|-------------|--------|
| **Jupyter** | Interactive notebooks | [jupyter/jupyter](https://github.com/jupyter/jupyter) |
| **Apache Zeppelin** | Web-based multi-language notebook | [apache/zeppelin](https://github.com/apache/zeppelin) |
| **Querybook** | Collaborative SQL notebook (Pinterest) | [pinterest/querybook](https://github.com/pinterest/querybook) |
| **SQLPad** | Web-based SQL editor | [sqlpad/sqlpad](https://github.com/sqlpad/sqlpad) |

## Infrastructure / Compute

| Tool | Description | GitHub |
|------|-------------|--------|
| **Apache Arrow** | In-memory columnar format | [apache/arrow](https://github.com/apache/arrow) |
| **Ray** | Distributed compute framework | [ray-project/ray](https://github.com/ray-project/ray) |
| **Dask** | Parallel computing in Python | [dask/dask](https://github.com/dask/dask) |
| **MinIO** | S3-compatible object storage | [minio/minio](https://github.com/minio/minio) |

---

## Contributing

PRs are welcome! If you know of an open-source tool that fits the modern data stack and is missing from this list, feel free to open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
