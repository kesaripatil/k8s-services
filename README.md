# k8s-services
To implement different service types available in K8S

# To access the cluster ip service
kubect port-forward svc/nginx-clusterip 8080:80

# To access the nodeport service on local using minikube
minikube service nginx-nodeport-svc

# To access the loadbalancer service
minikube tunnel

