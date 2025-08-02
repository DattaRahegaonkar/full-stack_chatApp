FROM node:18-alpine

WORKDIR /app

COPY package.* ./

RUN npm install

ENV NODE_ENV=production

COPY . .

EXPOSE 5001

CMD ["npm", "start"]

