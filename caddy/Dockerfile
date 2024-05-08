FROM caddy

RUN apk update
RUN apk add mc

WORKDIR /etc/caddy

COPY ./Caddyfile .
