FROM node:7-alpine
RUN yarn global add webpack@^1.14.0
RUN yarn global add webpack-dev-server@^1.16.2
RUN mkdir -p /app/user/
WORKDIR /app
ADD package.json ./package.json
RUN yarn
ADD . /app/user/
WORKDIR /app/user/
