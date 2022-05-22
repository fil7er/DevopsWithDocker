So i created a simple expressjs project in scrach, these my changes to dockerise the app

- Dockerfile

FROM node:8.16.1-alpine
WORKDIR /app
COPY . /app
RUN npm install
EXPOSE 5000
CMD node index.js


build , push on hub

create docker-compose.yml and add nginx proxy