FROM mjgargani/puppeteer:trybe1.0 AS todotests

EXPOSE 3000

ADD node_modules.tar.gz /app/

COPY . /app/

WORKDIR /app

ENTRYPOINT [ "npm" ]

CMD ["test"]