### Problem statement

In this project the goal is to build an end to end data pipeline. The project is broken down into 5 main components

1. Select a dataset that you're interested in (see [datasets.md](datasets.md))
2. Create a pipeline for processing this dataset and putting it to a datalake
3. Create a pipeline for moving the data from the lake to a data warehouse
4. Transform the data in the data warehouse: prepare it for the dashboard
5. Create a dashboard  with two tiles


## Data Pipeline 

The pipeline could be stream or batch: this is the first thing you'll need to decide 

* If you want to consume data in real-time and put them to data lake - go with stream.
* If you want to run things periodically (e.g. hourly/daily), go with batch


## Technologies used


* Cloud: AWS, GCP, Azure or others
* Infrastructure as code (IaC): Terraform, Pulumi, Cloud Formation, ...
* Workflow orchestration: Airflow, Prefect, Luigi, ...
* Data Wareshouse: BigQuery, Snowflake, Redshift, ...
* Batch processing: Spark, Flink, AWS Batch, ...
* Stream processing: Kafka, Pulsar, Kinesis, ...



This project is done after going through the course material from [Data-engineering-zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp/)
