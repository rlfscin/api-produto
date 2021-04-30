FROM node:15.14.0-alpine3.13
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY . .
EXPOSE 8080
CMD ["node", "app"]