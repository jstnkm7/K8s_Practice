## Kubernetes Cluster 
# Contains MongoDB and MongoExpress containers

Note for self:

Be sure to create configmap and secret objects before deploying mongoexpress and mongodb deployment since the deployment yaml contains environmental variables

Mongoexpress service for external ip adress will say <pending>
be sure to use minikube command

`minikube service mongoexpress-service`