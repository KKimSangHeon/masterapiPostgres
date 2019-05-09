create process
kubectl create -f postgres-configmap.yaml 
kubectl create -f postgres-storage.yaml 
kubectl create -f postgres-deployment.yaml 
kubectl create -f postgres-service.yaml 

delete process
# kubectl delete service postgres 
# kubectl delete deployment postgres
# kubectl delete configmap postgres-config
# kubectl delete persistentvolumeclaim postgres-pv-claim
# kubectl delete persistentvolume postgres-pv-volume
