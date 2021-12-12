# microservices-lab01

HOW TO START GIRAFFE.API DOCKER CONTAINER:

sudo docker build -t giraffe-app .

sudo docker run -p 5000:5000 -p 5001:5001 -v "Path to certificate.json with ssl trust cert":/https/ giraffe-app
