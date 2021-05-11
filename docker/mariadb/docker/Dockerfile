FROM mariadb


MAINTAINER yixuan<fanyixuanf@gmail.com>
LABEL Description="This image is used to start an MariaDB for Laravel." Vendor="yixuan" Version="1.0"

# Initializing a fresh instance by putting scripts into /docker-entrypoint-initdb.d
#COPY ./sql /docker-entrypoint-initdb.d/

CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_unicode_ci"]
