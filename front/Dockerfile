FROM node:10.7.0

WORKDIR /app
RUN npm install -g @vue/cli
ADD ./docker-practice/package.json /app/package.json
RUN npm install
ADD ./docker-practice/start.sh /app/start.sh
