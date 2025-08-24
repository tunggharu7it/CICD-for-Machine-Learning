# CICD-for-Machine-Learning

## Overview
**CICD-for-Machine-Learning** is a project demonstrating how to automate the training, evaluation, and deployment of machine learning models using **GitHub Actions** for Continuous Integration and Continuous Deployment (CI/CD). This repository provides a practical implementation of **MLOps** principles, enabling reproducible and scalable ML workflows—ideal for banking and business applications requiring robust model deployment.

---

## Features
- **Automated CI/CD Pipeline**: Uses GitHub Actions to automate model training, testing, and deployment.
- **Model Training & Evaluation**: Implements a supervised learning pipeline with metrics tracking (e.g., accuracy, F1-score).
- **Containerized Deployment**: Leverages Docker for consistent model deployment across environments.
- **Unit Testing**: Includes unit tests for model performance and data preprocessing steps.
- **Scalable Architecture**: Designed to integrate with microservices and APIs (e.g., FastAPI).

---

## Technologies Used
- **Programming**: Python 3.8+
- **ML Frameworks**: scikit-learn, TensorFlow
- **CI/CD**: GitHub Actions
- **Containerization**: Docker
- **Other Tools**: Pytest, MLflow (for experiment tracking)

---

## Getting Started

### Prerequisites
- Python 3.8+
- Docker
- GitHub account with Actions enabled
- MLflow server (optional, for experiment tracking)

### Installation
```bash
# Clone the repository
git clone https://github.com/kingabzpro/CICD-for-Machine-Learning.git
cd CICD-for-Machine-Learning

# Install dependencies
pip install -r requirements.txt

# Build Docker image
docker build -t ml-cicd:latest .
```
## Pipeline


![CICD](./asset/CICD-pipeline.png)

## Results
| Model                  | Accuracy | F1 Score |
|------------------------|----------|----------|
| RandomForestClassifier | 97.0%    | 94.0%    |

![CM](./Results/model_results.png)
