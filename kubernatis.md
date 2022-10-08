# How To check pods details
kubectl get pods -o wide

# How To Delete Pods
kubectl delete pod name of the Pod

# How To Check Pods
kubectl get pods

# How to describe Pods
kubectl describe pods pods name

# How to short Alias
alias  k="kubectl"

# how to create deployment
kubectl create Deployment nginx nginx-deployment --image=nginx

# how to describe deployment

kubectl describe deployment nginx-deployment



# how to check deployment 
 kubectl get deploy

 # how to check services
  kubectl get svc

  #  how to check deployment 
  kubectl create deployment deployment name  


# how to run container
minikube service deployment name 


# how to expose 
 kubectl expose deployment name of the deployment --type=NodePort --port=3000

 # how to create deployment 
 kubectl create deployment name --image=name of the image 

 curl -l http//: