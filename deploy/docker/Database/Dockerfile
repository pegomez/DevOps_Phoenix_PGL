FROM mongo:3.4

MAINTAINER pegomez.lopez@gmail.com

COPY drop/* usr/local/data/db/

CMD ["mongod", "--smallfiles", "--rest"]