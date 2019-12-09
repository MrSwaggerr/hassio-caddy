ARG BUILD_FROM
FROM $BUILD_FROM

ENV LANG C.UTF-8

RUN apk add --no-cache caddy=1.0.3 jq coreutils

ENV CADDYPATH /ssl

COPY run.sh /

CMD [ "/run.sh" ]
