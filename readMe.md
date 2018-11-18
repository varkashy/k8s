"# k8s"
https://kubernetes.io/docs/reference/kubectl/overview/

minikube start
minikube docker-env
@FOR /f "tokens=*" %i IN ('minikube docker-env') DO @%i
docker version
kubectl version
kubectl getpods
minikube --help
kubectl --help
kubectl get pods
kubectl describe hello-pod
kubectl describe pod hello-pod
kubectl version --output=yaml
kubectl create -f rs.yaml
kubectl get rs/web-rs
kubectl get pods --show-labels
kubectl --help
kubectl create --help

---------------

kubectl delete rs/web-rs --cascade=false
kubectl get rs
kubectl get pods show-labels
kubectl get pods --show-labels
kubectl create -f rs.yaml