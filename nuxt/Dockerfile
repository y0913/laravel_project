FROM node:14.4.0-alpine

# docker-compose.ymlから渡されてくる変数
ARG WORKDIR
ARG CONTAINER_PORT

ENV HOME=/${WORKDIR} \
    LANG=C.UTF-8 \
    TZ=Asia/Tokyo \
    HOST=0.0.0.0

WORKDIR ${HOME}

EXPOSE ${CONTAINER_PORT}