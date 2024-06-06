FROM node:17-alpine

WORKDIR /app

COPY pakage.json .

RUN npm install

COPY . .

EXPOSE 4000
# required for docker desktop port mapping

CMD ["node", "app.js"]