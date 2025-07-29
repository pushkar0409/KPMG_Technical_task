# NASA Near-Earth Objects (NEO)
This project demonstrates the ingestion, transformation, and analysis of Near-Earth Object (NEO) data using NASA's NeoWs public API, Python, pandas, matplotlib, seaborn, and Apache Spark. The workflow shows how to collect raw asteroid/comet data, process it for analytics, and store structured outputs suitable for data exploration and reporting.

## Overview
This repository contains code to:
- Fetch NEO data for user-defined date ranges from the NASA NEO Feed API.
- Explore and transform the hierarchical JSON response into flat tables for analytics.
- Load and process the data in Apache Spark for scalable analysis.- 
- Build tables (“objects”, and “obj_close_approaches”) supporting asteroid-level and event-level exploration. 
- Application of User Story 1 and 2

## If More Time Was Available
- Automate the Data Pipeline (ETL)
The current workflow involves manually running the notebook for a specified date range. If I had more time, I would use scheduled jobs and modular functions to create a fully automated ETL pipeline. Near real-time data availability would be made possible by ensuring continuous, hands-off data ingestion and transformation.
- Expand the Analysis Timeframe
The analysis currently spans only two days of NEO data. Given more time, I would extend the data collection across multiple months or years. This broader dataset would allow for richer trend analysis and improved statistical insights into near-Earth object activity.
- Enhance the Dataset
I would incorporate additional data from supplemental astronomical databases to further the analysis. To provide a more comprehensive scientific picture, this would entail including orbital parameters (such as semi-major axis, inclination, and eccentricity) in addition to contextual or physical characteristics pertinent to each NEO.
- Create Dashboards That Are Interactive
I would design interactive dashboards with programs like Tableau or Power BI to enable dynamic examination of important metrics and trends.
- Apply AI and Machine Learning
With a more comprehensive dataset, I would apply advanced analytical methods, such as time series forecasting, to predict future close approach frequencies. Additionally, I would design risk scoring mechanisms and automated alerts to highlight potentially hazardous events, enhancing proactive monitoring and response.

### Note - Please run the file in Databricks, as it includes some Databricks-specific visualizations and I was advised to use Databricks as the preferred environment.
