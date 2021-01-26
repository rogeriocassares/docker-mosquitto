FROM eclipse-mosquitto:2.0.1-openssl

MAINTAINER roger10cassares <roger10cassares@gmail.com>

RUN apk update \ 
    && apk add tzdata

ENV TZ=America/Sao_Paulo

EXPOSE 1883 8883 9001 9002
