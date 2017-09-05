### Start Containers

Task | Command
--- | --- 
Start a container | docker container run [image-name]
Start a container with the host's port 8080 mapped to the container's port 80 | docker container run -p 8080:80 run [image-name]
Start an "httpd" container with a specified name of "webserver" | docker container run --name webserver httpd
Start a container with an interactive terminal at a bash prompt | docker container run -it [image-name] /bin/bash
Start a new terminal on a running container | docker container exec -it [container-name] /bin/bash

### Inspect Containers

Task | Command
--- | ---
See all running containers | docker container ls or docker ps 
See all containers (including stopped) | docker container ls -a or docker ps -a 
See all running processes on a container | docker container top [container-name] 
See the logs from a running container | docker container logs [container-name]
See the configuration information for a container | docker container inspect [container-name]
Output a specific value from the docker configuration info | docker container inspect --format
Display stats about a all running containers | docker container stats
Display stats about a single running container | docker container stats [container-name]
