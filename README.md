Udacity DevOps Capstone project
---------------------------------- 

This project is about creating an image of an application, containerize it and deploy in using blue-green deployment pattern. Here I have used the knowledge gained for 

#How to run the project
* Please follow to steps as given in the 'screenshots of steps' folder.
The deployed project can be seen in:
http://a4c8819aacce64df3b7c105a9cbca889-404946795.us-west-2.elb.amazonaws.com:8000/

#Tools and utilities used
* AWS account
* Jenkins with Bleue Ocean and AWS plugins
* Docker
* Pip
* tidy
* AWS cli
* Eksctl
* Kubectl
* GitHub
* DockerHub

#Project works

In this project, I have been able to:
* Create clusters for a well orchestrated deployment
* Lint my application
* Build a Docker image of my application
* Upload the image to DockerHub
* Used the image to spin up containers
* Facilitate a blue-green deployment


#Files/folders included
* Pipeline1_create cluster/ : Pipeline to build the infrastructure
* Pipeline2_deployment/ : Pipeline for deployment
* Jenkinsfile : To design the pipelines
* Dockerfile : For building the image of the application
* green-controller.json : green-pod replication controller
* green-service.json : green service
* blue-controller.json : blue-pod replication controller
* blue-service.json : blue service
* index.html : index file of the website. 
* screenshots of steps/ : Screenshots of the steps covered in the project


