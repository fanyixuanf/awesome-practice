FROM redis

MAINTAINER yixuan<fanyixuanf@gmail.com>
LABEL Description="This image is used to start an Redis for Laravel." Vendor="yixuan" Version="1.0"

COPY ./docker/config/redis.conf /usr/local/etc/redis/redis.conf

CMD [ "redis-server", "/usr/local/etc/redis/redis.conf" ]