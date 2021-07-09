# docker

도커 사용하면서 필요했던 내용들 모아두었습니다

도커 이미지 가져오기

    docker pull [images name]

도커 이미지 조회

    docker images

도커 이미지 삭제

   docker rmi [image id]

도커 이미지 기반 실행

    docker run -it --rm -v [volume]:[docker volume] -p [portnum]:[docker portnum] [image name]:[tag]

docker 이미지 빌드

    # Dockerfile 내에서
    docker build --tag [name]:[tag] [Dockerfile directory]

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


## dockerfile 명령어

FROM

WORKDIR

RUN

ENTRYPOINT

CMD

EXPOSE

COPY/ADD

ENV

ARG
