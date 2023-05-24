## Example Voting App Kubernetes

This is based on the original [example-voting-app](https://github.com/dockersamples/example-voting-app) repository from the [docker-examples](https://github.com/dockersamples) GitHub page

and modified it to work on the Kubernetes cluster.

## To deploy follow these steps:
kubectl create -f filename
1. voting-app-deploy.yaml
2. voting-app-service.yaml
3. result-app-deploy.yaml
4. result-app-service.yaml
5. postgres-deploy.yaml
6. postgres-service.yaml
7. redis-deploy.yaml
8. redis-service.yaml
9. worker-app-deploy.yaml

## To get url when running minikube,use following commands
minikube service result-service --url

minikube service voting-service --url

## Output
![image](https://github.com/abdullahafeez/k8s_votingapp_example/assets/123733124/746403c7-24a1-4bd8-8374-c5c6595d1276)
