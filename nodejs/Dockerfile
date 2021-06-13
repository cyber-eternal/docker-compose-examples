# This image caches dependencies for other containers
# It allows to install them once and reuse later
FROM node:14 AS node_base

## Install deps
FROM node_base as deps
WORKDIR /usr/app
COPY package.json ./
RUN yarn install --frozen-lockfile && yarn cache clean

## Run app for DEV env
FROM node_base as build
WORKDIR /usr/app
COPY --from=deps /usr/app/node_modules /usr/app/node_modules
COPY . .
CMD yarn start
EXPOSE 3000
