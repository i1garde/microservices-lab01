# microservices-lab01

HOW TO START GIRAFFE.API DOCKER CONTAINER:

sudo docker build -t giraffe-app .

sudo docker run -p 5000:5000 -p 5001:5001 -v "Path to certificate.json with ssl trust cert":/https/ giraffe-app

HOW TO START FABLE.APP DOCKER CONTAINER:

sudo docker build -t fable-app .

sudo docker run -it -p 8080:8080 fable-app

TO ACCESS FABLE.APP GO TO THE http://0.0.0.0:8080
