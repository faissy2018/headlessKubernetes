This repositry contains Docker and Kubernetes files to run headless chrome in docker container and kubernetes.

For docker container 

docker run -p 3000:3000 faisal2018/headlessbrowserfaisal


For kubernetes

kubectl apply -f deployment.yml
Kubectl apply -f service.yml

