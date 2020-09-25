## Project Overview

In this project you will apply the skills and knowledge which were developed throughout the Cloud DevOps Nanodegree program. These include:

* Working in AWS
* Using Jenkins to implement Continuous Integration and Continuous Deployment
* Building pipelines
* Working with Ansible and CloudFormation to deploy clusters
* Building Kubernetes clusters
* Building Docker containers in pipelines

---

## Project Steps

* Launch two AWS EC2 instances for Jenkins, and EKS Cluster, respectively, and corresponding security groups are configured with right ports (ScreenShot00)
* Execute linting step in code pipeline, and include both a failed Linting screenshot and a successful Linting screenshot to show the Linter working properly
 (ScreenShot01 and ScreenShot02)
* Build a Docker container in the pipeline, run and test app in Docker, and push image to DockerHub
* Create ECR repositary and push image to ECR
* Deploy to EKS Cluster (ScreenShot03)

---

## Project Files

* views directory and index.html therein to store the web page
* Dockerfile used for building images
* Jenkinsfile to construct the pipeline
* README.md containing project summary
* app-deployment-aws.yml and app-deployment.yml to deploy app and sevice to Kubernetes Cluster (both AWS EKS Cluster and local)
* run_docker.sh for running a container (./run_docker.sh)
* run_kubernetes.sh to deploy with Kubernetes (./run_kubernetes.sh)
* upload_docker.sh for uploading an image to docker (./upload_docker.sh)
