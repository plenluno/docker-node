FROM plenluno/node
MAINTAINER Plenluno
RUN mkdir /example && curl https://raw.githubusercontent.com/plenluno/docker-node/master/example/app.js > /example/app.js
EXPOSE 8080
CMD ["node", "/example/app.js"]
