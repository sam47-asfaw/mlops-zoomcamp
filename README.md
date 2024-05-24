# Machine Learning Operations Zoomcamp by DataTalksClub
##### (This README file will be continously updated along with the DataTalksClub #MLOPS-Zoomcamp course progresses.)
#### Machine Learning Operations (MLOps) is the practice of streamlining the machine learning lifecycle to enable collaboration, automation, and continuous delivery of machine learning models at scale. It encompasses processes, tools, and best practices that facilitate the development, deployment, monitoring, and management of machine learning models in production environments. Key components of MLOps include:
* Data Management: Effective MLOps requires robust data management practices to ensure data quality, consistency, and security throughout the machine learning lifecycle. This includes data ingestion, preprocessing, labeling, versioning, and governance.
* Model Development: MLOps emphasizes collaboration and reproducibility in model development. Teams use version control systems, such as Git, to track changes to code and models. Automated testing and validation processes help ensure model accuracy, performance, and fairness.
* Model Deployment: MLOps automates the deployment of machine learning models into production environments. Containerization technologies, like Docker and Kubernetes, are commonly used to package models into portable and scalable containers. Continuous integration and continuous deployment (CI/CD) pipelines automate the deployment process, enabling rapid and reliable delivery of models into production.
* Monitoring and Logging: MLOps involves monitoring model performance and health in real-time to detect issues, such as concept drift, data drift, or model degradation. Logging and instrumentation frameworks capture relevant metrics, logs, and alerts to facilitate troubleshooting and optimization.
* Scalability and Efficiency: MLOps aims to optimize resource utilization and scalability by leveraging cloud computing, distributed computing, and infrastructure-as-code (IaC) practices. Autoscaling, load balancing, and resource provisioning ensure that computational resources are allocated efficiently to meet varying workload demands.
* Governance and Compliance: MLOps addresses governance, compliance, and ethical considerations related to machine learning models. This includes privacy protection, regulatory compliance, bias mitigation, and model explainability. Auditing and traceability mechanisms track model usage, changes, and lineage for accountability and transparency.

In summary, MLOps enables organizations to accelerate the development and deployment of machine learning models while ensuring reliability, scalability, and compliance with regulatory requirements. It fosters collaboration between data scientists, engineers, and operations teams, leading to more efficient and effective machine learning workflows.


## Table of Contents

- [ProjectStructure](#projectstructure)
- [01-Introduction](#01-Introduction)
- [02-Experiment-Tracking-with-MLFlow](#02-Experiment-Tracking-with-MLFlow)
- [03-Training-Pipelines](#03-Training-Pipelines)
- [04-Deployment](#04-Deployment)
- [05-Monitoring](#05-Monitoring)
- [06-Best-Practices](#06-Best-Practices)


## ProjectStructure
[README](https://github.com/sam47-asfaw/mlops-zoomcamp/blob/main/README.md): Contains all information about the course.

1. [01-Introduction](https://github.com/sam47-asfaw/mlops-zoomcamp/blob/main/README.md) :Introduction to MLOPS
   
2. [02-Experiment Tracking with MLFlow](https://github.com/sam47-asfaw/mlops-zoomcamp/blob/main/README.md) : Working with MLFlow 
   
3. [03-Training-Pipelines](https://github.com/sam47-asfaw/mlops-zoomcamp/blob/main/README.md): Training Pipelines

4. [04-Deployment](https://github.com/sam47-asfaw/mlops-zoomcamp/blob/main/README.md) : Local and Cloud Deployment 

5. [05-Monitoring](https://github.com/sam47-asfaw/mlops-zoomcamp/blob/main/README.md) : Monitoring ML-based services with Prometheus, Evidently, and Grafana

6. [06-Best-Practices](https://github.com/sam47-asfaw/mlops-zoomcamp/blob/main/README.md) : Best Practices


## 01-Introduction
###### The MLOps maturity level model is a framework used to assess and improve the maturity of an organization's machine learning operations (MLOps) practices. It consists of several levels, each representing a stage of maturity in how machine learning models are developed, deployed, monitored, and maintained within the organization. Here's a brief overview of the typical maturity levels in the MLOps model:

###### Level 0 - Ad Hoc: At this level, there is no formal process for managing machine learning models. Data scientists work independently, and models are developed and deployed manually without standardized processes or tools.

###### Level 1 - Initial: In this stage, the organization starts to recognize the need for formalizing MLOps practices. Basic version control and model documentation may be introduced, but processes are still ad hoc and inconsistent.

###### Level 2 - Managed: At this level, the organization implements more structured processes for managing machine learning models. This includes version control, automated testing, and continuous integration and deployment (CI/CD) pipelines. However, these processes may still be siloed within individual teams.

###### Level 3 - Defined: In this stage, the organization establishes standardized MLOps practices across teams and projects. There are clear guidelines and documentation for model development, deployment, and monitoring. Collaboration between data scientists, engineers, and operations teams is encouraged.

###### Level 4 - Optimized: At the highest level of maturity, the organization continuously improves its MLOps practices based on feedback and data-driven insights. This includes optimizing model performance, automating infrastructure provisioning, and implementing advanced monitoring and governance mechanisms.

###### The MLOps maturity level model helps organizations assess their current state of MLOps maturity and identify areas for improvement. By progressing through the maturity levels, organizations can enhance the efficiency, reliability, and scalability of their machine learning workflows, ultimately driving better business outcomes.
###### For more reference check this [article](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/guide/mlops-maturity-model)

## 02-Experiment-Tracking-with-MLFlow
##### ML Experiment is the process of building a ML model.
 ##### Experiment Tracking is important for:
      A: Reproducibility
      B: Organization
      C: Optimization
##### Why not use Spreadshit to track ML Experiment?
 ###### Spreadshit is not optimal to use ML Experiments because:
   ###### It is Error Prone
   ###### It has no Standard Format
   ###### Limited Visibility and Collaboration
##### [MLFLow](https://mlflow.org/) is an open source platform for machine learning platform
##### MLFlow is a python package that can be installed with pip and it contains four main modules:
###### Tracking
###### Models
###### Model Registry
###### Projects
###### Installing MLflow
##### ``` pip install mlflow ```
##### Running MLflow
``` mlflow ui --backend-store-uri sqlite:///mlflow.db ```


## 03-Training-Pipelines
   
## 04-Deployment

## 05-Monitoring

## 06-Best-Practices
