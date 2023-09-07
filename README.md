HOW TO RUN DOCKER COMPOSE

docker compose -f docker-compose.yml up : ini dia running di terminal log
docker compose -f docker-compose.yml up -d : dia running background AKA detact
docker container ls |grep app : mencari container yang mengandung nama app
docker exec -it app sh : ini untuk masuk ke dalam mode interractive shell container
docker container logs nama_container

Recomended to Build And RUN
docker compose -f docker-compose.yml up -d 