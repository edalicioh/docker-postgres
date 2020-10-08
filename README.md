# Docker Postgres

![docker](https://img.shields.io/badge/docker-compose-brightgreen "docker") ![banco](https://img.shields.io/badge/banco-postgres-green "banco")

`sudo docker cp <arquivo> <container>:<arquivo>`  

`sudo docker exec -it  <container>  pg_restore -U postgres  -d <banco> <arquivo> `

` sudo docker exec -it  <container>  psql -U postgres -d <banco>`
