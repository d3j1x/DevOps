FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSED 3000

CMD ["node","index.js"]
