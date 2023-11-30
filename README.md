# MLOps Practicals
![MLOps](https://img.shields.io/badge/MLOps-black.svg?logo=github&?logoColor=blue)

## Practical-1: Study of Machine Learning Basics

### Overview
In this section, we delve into the basics of machine learning, covering essential topics such as data collection, preprocessing, various machine learning models, and validation metrics.

## Practical-2: Introduction to Reproducible MLOps

### Overview
This practical focuses on reproducible machine learning operations, ensuring consistency in data processing and model deployment.

#### Tasks:
1. **Install Required Libraries**
   - Ensure numpy, scikit-learn, and matplotlib are available. Create requirements.txt and specify library versions.

2. **Import Sample Data and Apply Processes**
   - Use Python to import Sample.txt data.
   - Scale the dataset using StandardScaler for normalization.
   - Store the standard scaler object for reproducibility.
   - Split the normalized data into training and testing datasets.
   - Store a snapshot of the data as a numpy file for future use.
   - Address the question of ensuring the same random generation on each execution.

3. **Apply Linear Regression Algorithm**
   - Assess the prediction on the test dataset.
   - Store the trained model for reproducibility.
   - Import the model and test dataset into another Python file to ensure consistent predictions.
## Practical-3: Generation of Reproducible and Interactive ML Project using BinderHub

#### Task 1: Create GitHub Repository
Create a GitHub repository for the house rate prediction project created in Practical-2.

#### Task 2: Integrate with BinderHub
Integrate your repository with Binder to make your project interactive. Follow the steps in the [BinderHub Documentation](https://mybinder.org/) to achieve this.

#### Introduction to BinderHub
Briefly describe BinderHub and its benefits for interactive and reproducible computing environments.

## Practical-4: Introduction of Docker set-up and Study of Basic Docker Commands

#### Task 1: Install Docker CLI
Install the Docker Command Line Interface Tool from [Docker Documentation](https://docs.docker.com/desktop/).

#### Task 2: Hands-on on Docker Commands
Execute different Docker commands for pulling images, running containers, listing images and containers, and more.

## Practical-5: Deployment of ML Project using Flask

#### Task 1: Install Required Libraries
Install the Flask library following the [Flask Installation Guide](https://flask.palletsprojects.com/en/2.3.x/installation/).

#### Task 2: Deploy ML Model with Flask
Create templates, import model objects, and serve the deployment.

## Practical-6: Deployment of ML Project in Docker using Flask

#### Task 1: Install Required Libraries
Install the Docker CLI, Flask, and gunicorn. Refer to the following links:
- [Docker Documentation](https://docs.docker.com/desktop/)
- [Flask Installation Guide](https://flask.palletsprojects.com/en/2.3.x/installation/)
- [gunicorn Installation Guide](https://docs.gunicorn.org/en/latest/install.html)

#### Task 2: Create Docker Image and Run Container
Create a Dockerfile following the theory material. Build the Docker image and run the container using the gunicorn WSGI server.

#### Task 3: Compare Performance
Compare the performance of the model in the Docker container and Flask script deployment on a local server.

## Practical-7: Deployment of ML Project in Docker using Streamlit

#### Task 1: Install Required Libraries
Install the Docker CLI and Streamlit. Refer to the following links:
- [Docker Documentation](https://docs.docker.com/desktop/)
- [Streamlit Installation Guide](https://docs.streamlit.io/library/get-started/installation)

#### Task 2: Create Docker Image and Run Container
Create a Dockerfile following the theory material. Build the Docker image and run the container using the Streamlit app server.

#### Task 3: Compare Performance
Compare the performance of the model in the Docker container and Streamlit deployment on a local server.

## Practical-8: Study of Docker Swarm and Deployment of ML Project in Swarm Network

#### Prerequisites
- Three Linux host systems (e.g., Ubuntu)
- Docker installed on each host

#### Lab Steps
1. Initialize Docker Swarm
2. Join Worker Nodes
3. Deploy ML Model as a Service
4. Verify Deployment
5. Access ML Project
6. Scaling
7. Removing the Stack
8. Leave Swarm
9. Shut Down Host Systems

## Practical-9: Performing Basic Commands to Interact with Kubernetes

#### Prerequisites
- Running Kubernetes cluster
- `kubectl` command-line tool installed and configured

#### Lab Steps
1. Verify `kubectl` Configuration
2. List Nodes
3. Create a Deployment
4. List Pods
5. Access Pod Logs
6. Expose Deployment as a Service
7. List Services
8. Access the Service
9. Delete Resources
10. Scale Deployment
11. Update Deployment
12. Rollback Deployment

## Practical-10: Orchestration of ML Project Containers using Kubernetes

#### Prerequisites
- Running Kubernetes cluster
- `kubectl` command-line tool configured

#### Lab Steps
1. Verify Kubernetes Cluster
2. Define a Deployment using YAML Manifest
3. Describe Deployment
4. Expose Service
5. Access the Service
6. Scale Deployment
7. Update Deployment
8. Rollout Status
9. Rollback Deployment
10. Delete Resources

## Practical-11: Case Study of DevOps and Different Tools

#### Content 
Introduction  
Challenges   
DevOps Transformation 
Tools and Technologies  
Case Study  
Demo 
Benefits  
Conclusion  
Q&A 

## Practical-12: Case Study of Deep Learning Operations (DLOPs)

#### Content 
Introduction  
Challenges   
DataOps Implementation
Tools and Technologies  
Benefits  
Conclusion  
Q&A 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rajan2133/MLOps/HEAD)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/products/docker-desktop)

![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![](https://github.com/jupyterhub/repo2docker-action/workflows/Test/badge.svg) 
