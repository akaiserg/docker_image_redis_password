DOCKER REDIS
---------------------

Docker file for redis with config

Util commands
---------------------

docker build -t   my-redis .

docker run --name demo -p 6379:6379 -d my-redis

docker exec -it <id> bash

redis-cli  -h ip -p 6379

AUTH Y2Y1OWUzMjZmOGM0NjU3ODE4YmY0MDk3

redis-cli  -h ip -p 6379 -a Y2Y1OWUzMjZmOGM0NjU3ODE4YmY0MDk3 monitor

get requirepass


