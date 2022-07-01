# learnk8s

# reconfigure minikube

# 1 Stop minikube
minikube stop
# 2 Delete existing minikube
minikube delete
# 3 Remove config file
rm -rf ~/.kube
rm -rf ~/.minikube
# 4 Restart Minikube with additional memory as needed
minikube start --memory 4096 
