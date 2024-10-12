# Data-Platform-for-Ads-Optimization-with-Microservices-and-API-Development

The goal of this project is to develop a scalable data platform for an advertising business to optimize campaign performance. The platform will handle ads data ingestion, transformation, curation, and distribution, providing real-time metrics through APIs and dashboards for A/B testing, forecasting, and performance analysis.

## Technologies Used

- **Cloud Platforms:**
  - Google Cloud: BigQuery, Cloud Pub/Sub, Cloud Storage, GKE

- **Programming Languages:**
  - Python, SQL

- **Data Engineering Tools:**
  - dbt, Airflow

- **APIs and Microservices:**
  - FastAPI

- **Visualization:**
  - Looker

- **Machine Learning Libraries:**
  - Scikit-learn, Pandas, TensorFlow

- **Data Quality:**
  - Great Expectations


## Project Components

1. **Data Ingestion:**  
   Collect raw data from various sources into Google Cloud Storage and BigQuery.

2. **Data Transformation and Curation (with dbt):**  
   Use **dbt** to clean, transform, and curate the data for downstream processes.

3. **API and Microservice Development (FastAPI):**  
   Develop APIs and microservices using **FastAPI** to serve data and insights.

4. **A/B Testing Analysis:**  
   Perform A/B testing on experimental and control groups to measure campaign effectiveness.



## Features
- Data Ingestion with Google Cloud Pub/Sub
- Transformation and Curation with dbt
- API and Microservice Development with FastAPI
- A/B Testing with Python (SciPy)
- Forecasting with TensorFlow
- Visualization in Looker

## Setup Instructions
1. Clone the repository.
2. Set up Google Cloud credentials.
3. Install Python dependencies: `pip install -r requirements.txt`
4. Deploy the FastAPI app: `uvicorn api.main:app --reload`
5. **Forecasting Campaign Performance:**  
   Build predictive models to forecast future campaign performance using **Python** and **scikit-learn**.

6. **Dashboard Visualization in Looker:**  
   Create interactive dashboards with **Looker** for real-time visualization of key metrics.

7. **Deployment to Google Cloud:**  
   Deploy the entire pipeline using Google Cloud services like **GKE**, **BigQuery**, and **Cloud Storage**.
