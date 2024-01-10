FROM alpine:edge

RUN apk update \
    && apk update \
    && apk add --no-cache \
       snapcast-server

RUN mkdir /fifo
COPY snapserver.conf /etc/snapserver

EXPOSE 1704 1705

ENTRYPOINT ["snapserver"]
