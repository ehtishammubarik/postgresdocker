# Postgres with Docker 
docker-compose file is attached if you want to use compose to build run docker-container on your system. 
Dockerfile is attached if you want to use your config. 
to run dockerfile use 
docker build -t my-postgres:13 .
docker run -itd -v path/to/pgdata/and/config:/var/lib/postgresql/data -p 5432:5432 my-postgres:13 
docker ps (to verify running containers)
