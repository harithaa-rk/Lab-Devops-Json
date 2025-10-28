FROM node:22-alpine AS build
WORKDIR /app
COPY package*.json ./
RUN npm install
FOR nginx:console-alpine
COPY /app/dist /