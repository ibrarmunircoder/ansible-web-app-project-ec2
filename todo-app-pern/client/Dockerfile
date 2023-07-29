FROM node:16-alpine

LABEL author="IBRAR MUNIR"

WORKDIR /app

COPY ./package*.json ./

RUN npm install --only=production

COPY . .

CMD ["npm", "start"]