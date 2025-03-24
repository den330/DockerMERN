FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=nope
ENV MONGODB_PASSWORD=08500678

CMD ["npm", "start"]

