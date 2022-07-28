FROM nginx:alpine

COPY nginx.conf /etc/nginx/nginx.conf
COPY ./ca.pem /usr/local/share/ca-certificates/ca-oss-dev-cloud.pem
RUN update-ca-certificates

