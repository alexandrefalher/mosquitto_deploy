FROM alpine:3.11.6

RUN apk update && \
    apk upgrade && \
    apk add --no-cache mosquitto

EXPOSE 1883/tcp

CMD ["/usr/sbin/mosquitto"]
