# Capstone-Cloud-Devops-

Hi , This is my Capstone project for Udacity Cloud Devops nanodegree

this is the link to the application : a9235025f8ea14facb21d900b3ffe786-1462612341.us-east-1.elb.amazonaws.com:8080 

## Project Tasks:

* Working in AWS
* Using Jenkins to implement Continuous Integration and Continuous Deployment
* Building pipelines
* Working with CloudFormation to deploy clusters
* Building Kubernetes clusters
* Building Docker containers in pipelines

It has two pipelines


Pipeline1 : 1) authenticates into aws using jenkins aws plugin and creates an eks cluster.

Pipeline2 : 1)lints the html script
            2)Builds and uploads the docker image to dockerhub
            3)Sets up Kubernetes and deploys Blue and green Deployments


## Project Requirement:

            > To be able to use this CI/CD pipeline you will need to install:

            * Jenkins
            * Blue Ocean Plugin in Jenkins
            * Pipeline-AWS Plugin in Jenkins
            * Docker
            * Pip
            * AWS Cli
            * Eksctl
            * Kubectl

            ## The files included are:
            ```sh
            * /Images-of-work : Screenshot the result of deploy.
            * /Clusterformation : CloudFormation Script of Cluster Pipeline file
            * /Deployment pipeline : Deployment Script of Containers Pipeline file
            * Jenkinsfile : Jenkinsfile for Creating Pipeline
            * Dockerfile : Dockerfile for building the image
            * green-controller.json : Create a replication controller green pod
            * green-service.json : Create the green service
            * blue-controller.json : Create a replication controller blue pod
            * blue-service.json : Create the blue service
            * index.html : Web site Index file.
            ```

            ## Run the project:
            ```sh
            * Please follow to steps of screenshot in Images-of-result-deploy folder.
            ```
