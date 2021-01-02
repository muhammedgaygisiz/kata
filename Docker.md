# List all docker images

`docker images -a`

# Pull the mysql image from docker hub

`docker pull mysql`

# List all docker images

`docker images -a`

# Run container from image in background

`
docker run 
    --name mysql-container 
    -e MYSQL_ALLOW_EMPTY_PASSWORD=yes
    -p 3306:3306
    -d
    mysql
`

# Show running docker containers

`docker ps`

# Bash into container

`docker exec -it mysql bash`

# Stop Container

`docker stop mysql`