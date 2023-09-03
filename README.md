
# Docker in 10 minutes

We will be looking at the basics of Docker and learn how to build an image and run it in a container. We will be setting up nginx on our localhost as an example. 

We will also be learning about docker-compose and Dockerfile.

Docker Compose is a tool for defining and running multi-container docker applications. With compose, you use a yml file to configure your application's services.Then, with a single command, you create and start all the services from your configuration.

Docker can build images automatically by reading the instructions from a Dockerfile. A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image.




## Usage/Examples

You must change the value of the volumes in docker/docker-compose.yml to your root directory

You must change the value of the WORKDIR in docker/nginx/Dockerfile to your root directory

On your terminal, make sure you are inside the docker folder from your roor directory, then type:

```javascript
docker-compose up -d

