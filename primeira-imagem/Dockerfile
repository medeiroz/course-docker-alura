FROM node:20.6.1-bullseye

WORKDIR /app-node
EXPOSE 3000

COPY . .
RUN npm install

ENTRYPOINT npm start