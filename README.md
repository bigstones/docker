# docker

도커 사용하면서 필요했던 내용들 모아두었습니다

docker run -it --rm -v [volume]:[docker volume] -p [portnum]:[docker portnum] [image name]:[tag]

docker build --tag [name]:[tag] [repository]

docker-compose build

    docker-compose up -d --build
    
docker-compose down

    docker-compose down

docker 상태확인

    docker ps

docker cli 환경 접근

    docker exec -it [dockername] bash
    
log 확인

    docker logs --follow [dockername]
