# mastercloudapps-M3A2P2-k8s-microservices
Module 3 - Subject #2 - Assignment 2.

## Usage

Run
``` bash
$ cd kube/
$ kubectl apply -f all.yml
```

and then run
``` bash
$ minikube service server-service
```

### Running services individually
Alternatively, you can also run each service using different commands. 
Run this command for every service that you need to apply to your K8S cluster:
```bash
$ cd kube/individuals/
$ kubectl apply -f <name-of-service-file>.yml
```
and then, once all services have been applied, run
``` bash
$ minikube service server-service
```