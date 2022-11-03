# frontend file configuration

FROM node:17-alphine

WORKDIR /app

COPY package*.json .

#==== BUILD ===
RUN npm install

COPY . .

#==== RUN ===

EXPOSE 3000

CMD [ "npm","start"]


