# Docker

## To create an image follow the following commands
 
> docker build .
> docker images
> docker container run -d -p 8080:80 --name mycustomnginx ab8003bd374e
> docker ps

>>  localhost:8080
 
> docker container stop ab8003bd374e
> docker image rm ab8003bd374e -f