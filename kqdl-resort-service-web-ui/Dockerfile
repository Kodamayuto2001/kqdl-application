FROM node:17-alpine3.14

WORKDIR /var/www/html

RUN apk update && \
    npm install -g npm && \
    npm install -g @vue/cli

CMD cd app/ && \
    npm run serve
