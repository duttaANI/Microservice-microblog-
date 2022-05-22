# Microservice-microblogging APP

Run following commands in respective terminal for each service

$ npm start

$ docker build -t duttaani/event-bus .

$ docker run duttaani/event-bus  

$ minikube start

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
