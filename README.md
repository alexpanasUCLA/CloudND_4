
[![alexpanasUCLA](https://circleci.com/gh/alexpanasUCLA/CloudND_4.svg?style=svg)](https://circleci.com/gh/alexpanasUCLA/CloudND_4)

## Project Overview

In this project, I applied the skills acquired in this course to operationalize a Machine Learning Microservice API. 

I was given a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing).  This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

### Project Tasks

The projec goal is to take a working flask application that exposes API POST endpoint /predict to accept JSON payload and provide a prediction and do the following:
* test a code using linting (confirmed by the badge from CircleCI)
* write a Dockerfile to containerize the app 
* write a bash script to use a Dockerfile to create image and container and run it to make predictions
* improve log statement by editing scrypt in app.py 
* learn how to work with DockerHub and write a scrypt to delploy image to DockerHub
* configure local k8s using minikube and Virtual Box ( 1 node cluster) 
* deploy a container from DockerHub to k8s cluster (1 node) using imperative method, forward ports and make a prediction 
* integrated GitHub with CircleCI to make a basic pipeline to lint the code 


### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
