FROM nginx:1.21.0-alpine AS webserver
COPY dist/ /usr/share/nginx/html
RUN apk update
RUN apk add --no-cache vim curl
EXPOSE 80