# Scalable Machine Learning Pipeline on Google Cloud Vertex AI

## Overview

This project demonstrates the deployment, evaluation and comparison of machine learning models using Google Cloud Platform (GCP), Vertex AI and TensorFlow.

Using the Fashion-MNIST dataset, multiple image classification approaches were evaluated, including:

* A cloud-deployed TensorFlow model hosted on Vertex AI
* A locally hosted TensorFlow model
* A custom Convolutional Neural Network (CNN) trained from scratch

The project explores both cloud-native machine learning deployment workflows and model performance evaluation within a production-style environment.

---

## Technologies Used

* Python
* TensorFlow
* Google Cloud Platform (GCP)
* Vertex AI
* Google Cloud Storage
* NumPy
* Pandas
* Jupyter Notebook

---

## Key Features

* Cloud-based model deployment using Vertex AI
* Google Cloud Storage integration
* Vertex AI Model Registry usage
* Endpoint-based inference
* TensorFlow model evaluation
* Custom CNN development and training
* Model comparison and performance analysis
* Fashion-MNIST image classification

---

## Project Workflow

### 1. Cloud Storage Setup

A TensorFlow SavedModel was uploaded and stored in Google Cloud Storage.

![Cloud Storage Bucket](screenshots/bucket.png)

---

### 2. Model Registry Integration

The model was imported into Vertex AI Model Registry and configured for deployment.

![Model Registry](screenshots/model-registry.png)

---

### 3. Endpoint Deployment

The model was successfully deployed to a Vertex AI prediction endpoint, enabling cloud-hosted inference.

![Vertex AI Endpoint](screenshots/endpoint.png)

---

### 4. Vertex AI Workbench Environment

A dedicated Vertex AI Workbench instance was used for model evaluation and experimentation.

![Workbench Environment](screenshots/workbench-machine.png)

---

### 5. Model Artefacts

The deployed TensorFlow SavedModel consisted of standard TensorFlow artefacts including metadata, variables and model configuration files.

![Model Directory](screenshots/model-directory.png)

---

### 6. Dataset Structure

Training and testing datasets were organised for model evaluation and experimentation.

![Dataset Directory](screenshots/dataset-directory.png)

---

## Model Evaluation

Three approaches were evaluated:

| Model                    | Purpose                     |
| ------------------------ | --------------------------- |
| Vertex AI Deployed Model | Cloud-hosted inference      |
| Local TensorFlow Model   | Local deployment comparison |
| Custom CNN               | Performance optimisation    |

The project compared model behaviour across deployment environments while exploring scalable machine learning workflows.

---

## Skills Demonstrated

* Machine Learning
* Deep Learning
* Computer Vision
* Cloud Computing
* Model Deployment
* MLOps Fundamentals
* Data Processing
* TensorFlow
* Google Cloud Platform
* Vertex AI

---

## Repository Contents

| File                        | Description                            |
| --------------------------- | -------------------------------------- |
| vertex_ai_ml_pipeline.ipynb | Main project notebook                  |
| requirements.txt            | Python dependencies                    |
| screenshots/                | Deployment and infrastructure evidence |

---

## Academic Context

Developed as part of the Data Science at Scale module during the final year of BSc Computer Science at the University of Exeter.
