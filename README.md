# NASA Near-Earth Objects (NEO)
This project demonstrates the ingestion, transformation, and analysis of Near-Earth Object (NEO) data using NASA's NeoWs public API, Python, pandas, matplotlib, seaborn, and Apache Spark. The workflow shows how to collect raw asteroid/comet data, process it for analytics, and store structured outputs suitable for data exploration and reporting.

Overview
This repository contains code to:
- Fetch NEO data for user-defined date ranges from the NASA NEO Feed API.
- Explore and transform the hierarchical JSON response into flat tables for analytics.
- Load and process the data in Apache Spark for scalable analysis.- 
- Build dimensional tables (“objects”, and “obj_close_approaches”) supporting asteroid-level and event-level exploration. 
- Application of User Story 1 and 2

