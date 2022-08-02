FROM nextcloud:fpm-alpine
COPY ./ca.pem /usr/local/share/ca-certificates/ca-oss-dev-cloud.pem
RUN update-ca-certificates
