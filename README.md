# Devops Pro Docker Challenges
Repository to save Docker challenges


### Challenge 1 - Postgres
Command to execute ```docker run --name postgres_curso_docker -e POSTGRES_DB=curso_docker -e POSTGRES_USER=docker_usr -e POSTGRES_PASSWORD=docker_pwd -p 5432:5432 -d postgres```

### Challenge 2 - MySQL
Command to execute ```docker run --name mysql_curso_docker -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd -e MYSQL_ROOT_PASSWORD=root_pwd -p 3306:3306 -d mysql```

### Challenge 3 - MongoDB
Command to execute ```docker run --name mongo_curso_docker -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd -p 27017:27017 -d mongo```
