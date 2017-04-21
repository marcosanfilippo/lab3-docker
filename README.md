How to build a docker container for LAB3 (AI 2017 PoliTO)
***************************************************************
# docker pull mongo
# docker volume create VOLUME_NAME
# docker volume inspect VOLUME_NAME

Take volume path...
# docker run -v /PATH_TO_VOLUME:/CONTAINER_PATH_TO_VOLUME -p 21707:21707 mongo

Marco's PC:
# docker run -v /mnt/sda1/var/lib/docker/volumes/lab3_mongo/_data:/data/db -p 21707:21707 mongo

Log:
# docker logs -f CONTAINER_NAME

INTERACT WITH INTERNAL CONSOLE (INSIDE CONTAINER)
# docker exec -it CONTAINER_NAME bash
