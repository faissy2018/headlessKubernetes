To tun headless vnc in docker you can use the command

docker run --rm -ti -p 5901:5901 --name docker-ubuntu faisal2018/headlessvnc

password for vnc is vncpassword

for kubernetes

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
