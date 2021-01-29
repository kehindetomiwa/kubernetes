# Kubernetes
kubectl create -f deploy-backend.yaml

kubectl create service clusterip mongo --tcp=27017:27017

kubectl create -f deploy-frontend.yaml

kubectl create service nodeport front-end –-tcp=80:8888

getp ports
kubectl get svc front-end
# kubernetes
