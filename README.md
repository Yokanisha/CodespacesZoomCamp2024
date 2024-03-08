# CodespacesZoomCamp2024

<p align="center">
  <picture>
    <source srcset="https://github.com/risingwavelabs/risingwave/blob/main/.github/RisingWave-logo-dark.svg" width="500px" media="(prefers-color-scheme: dark)">
    <img src="https://github.com/risingwavelabs/risingwave/blob/main/.github/RisingWave-logo-light.svg" width="500px">
  </picture>
</p>


</div>

<p align="center">
  <a
    href="https://docs.risingwave.com/"
    target="_blank"
  ><b>Documentation</b></a>&nbsp;&nbsp;&nbsp;📑&nbsp;&nbsp;&nbsp;
  <a
    href="https://tutorials.risingwave.com/"
    target="_blank"
  ><b>Hands-on Tutorials</b></a>&nbsp;&nbsp;&nbsp;🎯&nbsp;&nbsp;&nbsp;
  <a
    href="https://cloud.risingwave.com/"
    target="_blank"
  ><b>RisingWave Cloud</b></a>&nbsp;&nbsp;&nbsp;🚀&nbsp;&nbsp;&nbsp;
  <a
    href="https://risingwave.com/slack"
    target="_blank"
  >
    <b>Get Instant Help</b>
  </a>
</p>


## What is RisingWave?
RisingWave is an open-source distributed SQL streaming database, offering a straightforward, effective, and dependable approach to handle streaming data. Under the Apache 2.0 license, it empowers developers to manage stream processing akin to database operations. With the ability to articulate complex processing logic through materialized views, developers can access constantly updated and coherent results by querying these views.

Users can use RisingWave for:
- Stream processing;
- Data storage;
- Random querying, especially point queries.

Users should not use RisingWave for：
- Transaction processing;
- Ad-hoc analytical queries that involve frequent full table scans.

![001](https://github.com/Yokanisha/CodespacesZoomCamp2024/blob/main/Image/001.jpg)

## Why RisingWave for stream processing?
RisingWave offers unparalleled benefits for stream processing with its focus on consistently updated materialized views and simplified development experience. By allowing developers to express complex processing logic through cascaded materialized views, RisingWave streamlines application development and eliminates the need for external storage solutions.

Compared to existing stream processing systems like Apache Flink, Apache Spark Streaming, and ksqlDB, RisingWave excels in ease-of-use and cost efficiency. Its PostgreSQL-style SQL interface makes it easy to learn and integrate into existing infrastructures. Additionally, RisingWave's architecture, reminiscent of Snowflake's separation of storage and compute, ensures efficient and transparent scaling, along with rapid failure recovery.

In essence, RisingWave offers a seamless and cost-effective solution for stream processing, empowering users to efficiently manage and query streaming data with ease.


![002](https://github.com/Yokanisha/CodespacesZoomCamp2024/blob/main/Image/002.jpg)



## Prerequisites

- Docker and Docker Compose
- Python 3.7 or later
- pip and virtualenv for Python
- psql (I use PostgreSQL-14.9)
- Clone this repository:
```
$ git clone https://github.com/risingwavelabs/risingwave-data-talks-workshop-2024-03-04.git
```

- Run some diagnostics.
- Start the RisingWave cluster.
- Setup our python environment.
```bash
# Check version of psql
psql --version
./commands.sh

# Start the RW cluster
start-cluster

# Setup python
python3 -m venv .venv
.venv/Scripts/activate
pip install -r requirements.txt
```


