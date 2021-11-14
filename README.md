

Implements example from here: https://www.bezkoder.com/docker-compose-spring-boot-mysql/#Create_Dockerfile_for_Spring_Boot_App 

##  Quick list of Docker Commands

docker compose build  : Use (first time) to build docker images from the docker-compose.yml file
docker compose up -d  : Start the docker containers
docker container ls   : List all running containers
docker compose down   : Stop the docker containers
docker exec -it container_it bash : Open a bash terminal in the container with the provided name