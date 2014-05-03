FROM plenluno/node
MAINTAINER Plenluno

# if you'd like to use another version of node,
# ENV NODE_VERSION vX.Y.Z
# RUN nodebrew install-binary $NODE_VERSION
# RUN nodebrew use $NODE_VERSION

# run your application
RUN mkdir /example && curl https://raw.githubusercontent.com/plenluno/docker-node/master/example/app.js > /example/app.js
EXPOSE 8080
CMD ["node", "/example/app.js"]
