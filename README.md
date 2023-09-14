# MicroservicesApp
A smaple ASP.NET core app which users react as FE, docker for hosting Rabbit MQ, Elastic Search.

# Docker Setup
docker build -t counter-image -f Dockerfile .
docker run -p 8080:80 <imagename>