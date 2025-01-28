# Exploring-YouTube-Trends-with-Data-Engineering
This project focuses on securely handling, optimizing, and analyzing structured and semi-structured YouTube video data. It categorizes and examines trending metrics to generate actionable insights. The key objectives include designing efficient data ingestion workflows, building a robust ETL pipeline, and establishing a scalable data lake for seamless storage and processing.

---

##  Core Features

- **Streamlined Data Ingestion**: Efficient workflows for processing YouTube video data.
- **Reliable ETL Pipeline**: Transform and load high-quality data for analysis.
- **Centralized Data Lake**: Scalable and flexible storage using AWS S3.
- **Integration with AWS**: Seamless data management using AWS Glue, S3, Lambda, and Athena.
- **Interactive Querying**: Use AWS Athena for dynamic data exploration.
- **Insightful Visualizations**: Visualize key metrics and trends using Amazon QuickSight.

---

##  Technologies Utilized

- **Programming**: Python  
- **AWS Services**: 
  - Amazon S3
  - AWS Glue
  - AWS Lambda
  - AWS Athena
- **Big Data Processing**: Apache Spark (PySpark)  
- **Data Manipulation**: Pandas  

---

##  Dataset

The project uses a dataset from [Kaggle](https://www.kaggle.com/), which contains comprehensive statistics on daily trending YouTube videos across various regions. Key data points include:  
- Video Titles  
- Publication Timestamps  
- Views, Likes, and Dislikes  
- Additional Metadata  

This dataset provides a rich source for analyzing trends and metrics.

---

##  Codebase Overview

### `lambda_function.py`
This script contains AWS Lambda code for managing:
- Data ingestion
- Data transformation
- Storage using AWS Glue and Amazon S3

### `etl_pyspark.py`
A PySpark-based script that:
- Performs ETL operations
- Ensures data quality and compatibility during transformations

---

##  How to Use

1. **Set Up AWS Configurations**:
   - Ensure proper permissions for AWS Glue, S3, Lambda, and Athena.
   - Configure necessary roles and policies in AWS.

2. **Trigger the Lambda Function**:
   - Use S3 events to automatically invoke the Lambda function for data ingestion and transformation.

3. **Run the ETL Pipeline**:
   - Execute the `etl_pyspark.py` script as part of an AWS Glue job or in a local Spark environment for further processing.

4. **Visualize and Query**:
   - Use AWS Athena for interactive querying.
   - Visualize results with Amazon QuickSight.

---

##  Contributing

Contributions are welcome! If you have suggestions or ideas for improvements:  
- Fork the repository  
- Create a new branch for your changes  
- Submit a pull request  

Feel free to open issues for any bugs or feature requests.
