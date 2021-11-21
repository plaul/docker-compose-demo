

Implements example from here: https://www.bezkoder.com/docker-compose-spring-boot-mysql/#Create_Dockerfile_for_Spring_Boot_App 

##  Quick list of Docker Commands

- `docker compose build`  : Use (first time) to build docker images from the docker-compose.yml file
- `docker compose up -d`  : Start the docker containers
- `docker container ls`   : List all running containers
- `docker compose down`   : Stop the docker containers
- `docker exec -it container_mysql bash` : Open a bash terminal in the container with the provided name


When cloned, either create (in the root) a .env file and set these variables (with our own values):
```
MYSQLDB_USER=root
MYSQLDB_ROOT_PASSWORD=123456
MYSQLDB_DATABASE=bezkoder_db
MYSQLDB_LOCAL_PORT=3307
MYSQLDB_DOCKER_PORT=3306
SPRING_LOCAL_PORT=6868
SPRING_DOCKER_PORT=8080
```
Alternatively set the environment-values anyway you like.