FROM node:14 AS todobackend

EXPOSE 3001

ADD node_modules.tar.gz /app/
COPY . /app/
WORKDIR /app

ENTRYPOINT [ "npm" ]

CMD ["start"]