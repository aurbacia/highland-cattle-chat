FROM library/nginx:stable-alpine3.20
COPY build/default.conf /etc/nginx/conf.d/
WORKDIR /usr/share/nginx/html
COPY dist/ .