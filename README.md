
# Fibonacci App Using Kubernetes

This Fibonacci App is created using Docker images and the architecture of the app is created using Kubernetes. It contains Deployments for client,server and worker and these deployments are connected using Cluster IPs. Redis and Postgres DB has been used for caching and storing respectively.

To run the app, type the below command :

kubectl apply -f k8s 


