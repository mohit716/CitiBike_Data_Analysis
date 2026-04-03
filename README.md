# CitiBike NYC Trip Analysis

Distributed big data analysis of 3.2M+ CitiBike rides using PySpark, MapReduce, and Spark SQL.

## Overview

Analyzed April 2024 CitiBike trip data using distributed computing techniques including PySpark RDDs, MapReduce jobs, and Spark SQL queries to uncover ridership patterns across New York City.

## Tech Stack

- **PySpark** — RDDs, DataFrames, Spark SQL
- **MRJob** — MapReduce jobs
- **Pandas / Seaborn** — aggregation and visualization
- **Google Colab** — execution environment
- **Parquet** — output format for downstream analytics

## Key Analyses

- Most popular start stations (MapReduce)
- Average trip duration by user type (member vs. casual)
- Ridership patterns by bike type and hour of day
- Commuter window identification
- 95th percentile trip durations via approximate aggregations

## Dataset

- Source: CitiBike system data (April 2024)
- Size: 3.2M+ rides
- Format: CSV → processed to Parquet

## How to Run

1. Open the notebook in Google Colab
2. Upload or mount the CitiBike dataset
3. Run cells sequentially

## Course

CS 660 — Data Analysis at Scale, Drexel University
