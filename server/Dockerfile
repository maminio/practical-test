ARG NODE_VERSION
ARG APP_VERSION


FROM node:${NODE_VERSION}-alpine

WORKDIR "/app"

COPY ./server/package.json ./
COPY ./server/yarn.lock ./
COPY ./server ./
RUN yarn install



CMD ["yarn", "debug"]
EXPOSE 9229
