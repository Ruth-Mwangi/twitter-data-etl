# twitter-data-etl
The purpose of the project is to efficiently collect, process, and store Twitter data using a combination of Apache Airflow, Apache Spark, and Amazon S3. 

## Prerequisites

Before setting up and running the Twitter Data Pipeline project, make sure you have the following prerequisites in place:

1. **Environment Setup:**
   - Install and configure Apache Airflow.
   - Install and configure Apache Spark on the target machine or cluster.

2. **Twitter Developer Account:**
   - Obtain Twitter API credentials by creating a Twitter Developer account.

3. **AWS Account:**
   - Create an AWS account to utilize Amazon S3 for storing processed data or any other storage you choose.

4. **Access and Permissions:**
   - Grant necessary permissions for Twitter API access and AWS S3 resources.

5. **Data Schema Understanding:**
   - Familiarize yourself with the structure of Twitter data returned by the API.

6. **Apache Airflow Plugins:**
   - Identify and install required Airflow plugins based on project needs.

7. **Spark Job Configuration:**
   - Develop Spark jobs and ensure the correct setup of dependencies and configurations.

8. **AWS S3 Bucket Configuration:**
   - Create S3 buckets for storing processed data and configure access policies.

9. **Logging and Monitoring:**
   - Configure logging within Spark jobs and set up monitoring tools in Airflow.

## Getting Started

Follow these steps to set up and run the Twitter Data Pipeline:

1. Clone the repository.
2. Install dependencies using the provided setup scripts.
3. Configure Airflow connections for Twitter API and AWS.
4. Set up Spark jobs based on project requirements.
5. Run the Airflow DAG to initiate the data pipeline.

