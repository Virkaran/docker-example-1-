commands to run
docker build -t username/node-app:v1 .


docker images


docker push username/node-app:v1


docker run -d -p 3000:3000 --name my-running-app username/node-app:v1


docker logs my-running-app
