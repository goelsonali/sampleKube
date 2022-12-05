# sampleKube
Simple spring-boot application using docker to package the app and kubernetes workloads to run the application.

#Docker container
Dockerfile

#Kubernetes changes
deployment.yaml

Note : To run the service you need to install minikube locally to create the kubernetes workloads

Some useful commands :
#To start minikube
minikube start
#To start your deployment and service in kubernetes
kubectl apply -f deployment.yaml
#To delete your deployment
kubectl delete -f deployment.yaml
 


