FROM node:alpine

WORKDIR /app

EXPOSE 5000

COPY package.json package-lock.json ./

RUN npm install

COPY . ./

CMD ["npm", "run", "dev"]
