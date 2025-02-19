FROM node:20-alpine
ENV NODE_ENV=development

WORKDIR /usr/src/app

COPY . .

RUN npm install \
    && npm run build

EXPOSE 3000
