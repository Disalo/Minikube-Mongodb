# MongoDB + Mongo-Express on MINIKUBE
### The repository includes .yaml files to how to deploy a simple application in a kubernetes(minikube) cluster.

### Here two applications are deployed: 1. Mongodb & 2. Mongo-express. The goal is to demonstrate a typical simple setup of a web application and its database.

## Steps to do:
### 1. Create mongo-secret.yaml to create secret containing authentications.
### 2. Create a mongodb pod referenced authentications from secret file.
### 3. Create an INTERNAL(just for components inside the cluster) service to talk to mongodb pod.
### 4. Create a configMap including mongodb address as an external configuration.
### 5. Create a mongo-express pod.
### 6. Create an EXTERNAL service to access mongodd through browser.  
