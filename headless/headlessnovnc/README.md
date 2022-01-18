TO use novnc in docker container

docker run --rm --name novnc -p 6080:6080 faisal2018/headlessnovnc

To use in kubernetes

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
