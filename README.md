# Steps by steps to create a Docker-image, Run as container and push to docker Hub
make sure you have docker installed
2- Create a folder and build a dockerfile in it
build the image. Syntax: docker build . or docker build -t <path to the dockerfile>
build the container. NB: Image becomes a container when it runs.
syntax: docker run -d -p 80:80 <image ID>            d is for daemon    p is for port 
Check if the container is running: docker ps
to stop your container: docker stop <container ID>   To restat it: docker start
to comletely remove a container from our machine: docker rmi <container ID>
To push in the dockerhub (ask chatgpt the syntax)
open your dockerhub and verify that the created container y exists.
