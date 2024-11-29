# **ELT Data Pipeline for Airbnb Analytics**
---
## **Introduction**
The goal of this project is to build production-ready ELT data pipeline using Apache Airflow and dbt Cloud, with the primary goal of processing and transforming Airbnb and Census data for Sydney. It aims to load this data into a data warehouse structured using the Medallion architecture (Bronze, Silver, Gold) and to create a data mart for analytical insights. Key aspects of the project include efficient data ingestion using Airflow, managing transformations through dbt Cloud, and designing a star schema to organize data in Postgres. Throughout the process, data is transformed from raw form into cleaned and aggregated tables, enabling detailed analysis and insights into rental trends, host behaviours, and demographic factors. The final data mart serves as the foundation for performing ad-hoc analyses that address business questions



## **Key objectives**
The main objective of this project is to develop robust ELT data pipelines using Apache Airflow and dbt Cloud to process and transform Airbnb and Census data for Sydney


## **Project workflow**
![Workflow](Workflow.png)



## **Tools and Technologies**
- Google Cloud Platform
- dbt Cloud
- Dbeaver
- Apache Airflow (via Cloud Composer)
- Python
- SQL



## **Dataset**
- [12 months of Airbnb listing data for Sydney](https://drive.google.com/file/d/1_AvGzOLrCNCnDJyStSj2XH0bTUtsKgb_/view)
- [Census LGA](https://drive.google.com/file/d/1AbfLWOCgPfAY8bBRX1blZdL0-dO2joXT/view): Table G01 (“Selected Person Characteristics by Sex”) and G02 (“Selected Medians and Averages”) of the General Community Profile Pack from 2016 census at the LGA level
- [NSW_LGA](https://drive.google.com/file/d/1y962EkNhG2nBGiMsV8sYN2BeFsIy6zO5/view): A dataset help you join both datasets based on LGAs code and a mapping between LGAs and suburbs.
