# frontend file configuration

FROM node:17-alpine

WORKDIR /app

COPY package*.json .

#==== BUILD ===
RUN npm install

COPY . .

#==== RUN ===

EXPOSE 3000

CMD [ "npm","start"]


