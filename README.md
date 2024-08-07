### Customer segmentation usign kubernetes

### Overview

This repository demonstrates the development of a scalable machine learning model for customer segmentation, designed for real-time inference via a REST API. The project addresses the business challenge of segmenting customers using unstructured data to devise personalized marketing strategies. It integrates sophisticated workflows, including data ingestion, transformation, model training, and deployment, utilizing advanced tools such as FastAPI, Docker, Kubernetes, and GitHub Actions.

### Business statement

Customer segmentation is crucial for businesses to comprehend and cater to the diverse needs of their customer base. By classifying customers according to their behaviors and characteristics, companies can customize marketing strategies to enhance customer engagement and retention. This project develops a machine learning model that segments customers and delivers real-time predictions through a REST API.

### WorkFlow

1. Data Ingestion: Load and prepare the customer dataset for analysis.
2. Data Transformation: Clean and preprocess the data to make it suitable for model training.
3. Model Training: Utilize the K-Means clustering algorithm to segment customers and determine the optimal number of clusters using the Elbow Method.
4. Real-Time Inference with FastAPI: Develop a REST API using FastAPI to serve the model and provide real-time predictions.
5. Containerization with Docker: Use Docker to containerize the FastAPI application, ensuring consistent deployment across various environments.
6. Deployment with Kubernetes: Deploy the containerized application to a Kubernetes cluster for scalability and high availability.
7. CI/CD Pipeline with GitHub Actions: Automate the build and deployment process using GitHub Actions, enabling continuous integration and continuous deployment.
8. Testing: Verify the model's performance and accuracy using Postman for API endpoint testing and a Gradio interface hosted on Hugging Face Spaces for user-friendly testing.


### How to run 

1. Clone this repositary

https://github.com/amolnayakawadi/Scalabel-Customer-Segmentation-using-Kubernetes-for-Enhance-market-analysis/tree/main

2. Set up Virtual Environment
conda create -n venv python==3.11 (your existing python version)

3. Install all dependencies 

pip install -r requirements.txt

4.Run Application locally 

python main.py 

uvicorn main:app --reload

