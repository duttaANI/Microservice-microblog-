# Microservice-microblogging APP

ubuntu -
/etc/hosts

insert following line-

192.168.58.2 posts.com

##### the above ip is recieved by following command-

❯ code /etc/hosts

❯ minikube ip

192.168.58.2

[https://kubernetes.github.io/ingress-nginx/deploy/#minikube](https://kubernetes.github.io/ingress-nginx/deploy/#minikube)

Run following commands in respective terminal for each service

$ npm start

$ docker build -t duttaani/event-bus .

$ docker run duttaani/event-bus  

$ minikube start

$ minikube addons enable ingress

$ kubectl version

$ kubectl apply -f posts.yaml 

$ kubectl get pods -o wide

$ kubectl exec posts -- it sh

$ kubectl delete pod posts

$ kubectl describe pod posts

$ kubectl get deployments

$ docker push duttaani/posts

$ kubectl rollout restart deployment posts-depl

$ kubectl logs posts-depl-6c745ddd69-t9xvg

$ kubectl get services

$ kubectl describe service posts-srv

$ kubectl apply -f .

$ minikube addons enable ingress

$ sudo lsof -i tcp:80

$ code /etc/hosts

$ minikube ip

$ scaffold dev



<p align="left">   
  <img src="./images/initial.png" width=70% height=70% />
</p>

<p align="left">
  <img src="./images/Query_Service.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/Moderation_service_stops.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/Event_Bus_Data_Store.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/Event_Bus_broadcast.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/docker_1.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/dock_2.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/dock_3.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/dock_4.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/dock_to_k8.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/docker_cmds.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/config_routing_rules.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/ingress1.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/ingress_controller.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/load_bal.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/load2.png" width=70% height=70% />
</p>

<p align="left">
  <img src="images/pods_view.png" width=70% height=70% />
</p>



