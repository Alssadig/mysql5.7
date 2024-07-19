# How to install Mysql on your local machine

1. Update .env file by adding user & root DB passwords
3. Install docker on your machine
4. Execute `docker network create mysql57`
5. Execute `docker volume create mysql57`
6. Execute `docker compose -f stack.local.yml up -d`
7. Execute `docker ps` and check if the container is running
8. Enjoy
