FROM node:14 AS todofrontend

EXPOSE 3000

ADD node_modules.tar.gz /app/
COPY . /app/
WORKDIR /app

ENTRYPOINT [ "npm" ]

CMD ["start"]