FROM node:18.16.0-alpine3.18
EXPOSE 3333
WORKDIR /app

RUN apk update && \
    apk upgrade

CMD ["npm", "run", "dev"]