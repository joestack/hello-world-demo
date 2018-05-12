# Test web-app for demo reason
# Linux x64
FROM alpine

LABEL maintainer="jstenkamp@mirantis.com"

# Install Node and NPM
RUN apk add --update nodejs nodejs-npm

# Copy app to /src
COPY . /src

WORKDIR /src

# Install dependencies
RUN  npm install

EXPOSE 8080

ENTRYPOINT ["node", "./server.js"]
