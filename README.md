# microservices-lab01

Start kuber cluster:

minikube start

HOW TO BUILD DOCKER CONTAINERS:

eval $(minikube docker-env)

sudo docker build -t giraffe:0.1 .

sudo docker build -t fable:0.1 .

ADD .YAML CONFIGURATIONS:

kubectl apply -f kubectl/fable

kubectl apply -f kubectl/giraffe

kubectl apply -f kubectl/ingress.yaml

TO DISCOVER ENTRYPOINT ENTER: echo $(minikube ip)

Fable app is available in the root directory and Giraffe-API at /api
