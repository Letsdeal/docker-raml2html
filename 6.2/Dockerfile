FROM node:7-alpine

RUN npm install -g raml2html@~6.2 \
 && npm cache clean

RUN mkdir -p /data
VOLUME /data
WORKDIR /data

ENTRYPOINT ["raml2html"]

CMD ["--help"]
