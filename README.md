Да, в курсе, что необходимо не скармливать .env в git
Но тут исключение, так как это является демонстрацией, где и как хранить


Быстрый запуск PostgreSQL через Docker Compose
https://habr.com/ru/articles/823816/


# Управляем всеми

docker stop $(docker ps -aq)

docker rm $(docker ps -aq)

docker-compose -f n8n.yml up --force-recreate -d
OR
docker-compose  up --force-recreate -d

