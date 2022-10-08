# how to check pods 
```bash
$ kubectl get pods
```
# how to connect minikube using ssh
```bash
$ minikube ssh
```
# how to minikube to open your browser
```bash
$ minikube service {your deployment name}
```
# how to check services
```bash
$ kubectl get svc
```
# how to check deploy
```bash
$ kubectl get deploy
```
# how to check pods details 
```bash
$ kubectl get pods -o wide
```
# how to apply deployment file
```bash
$ kubectl apply -f deployment.yml
```
# how to delete deployment file
```bash
$ kubectl delete -f deployment.yml
```
# how to apply multiple file
```bash
$ kubectl apply -f deployment.yml -f pod.yml
```

# how to manually deploy app
```bash
$ kubectl create deployment {deployment name} --image={image name} --port={port name}
```

# how to expose port 
```bash
$ kubectl  expose deployment {deployment name } --image={image name } --type=NodeType --port={your application port}
```