FROM node:12.16.2-alpine3.9 as builder


WORKDIR /app

COPY ./package.json ./

#RUN npm install -g yarn
RUN yarn install

COPY . .

EXPOSE 3000
EXPOSE 35729


CMD ["yarn", "start"]
