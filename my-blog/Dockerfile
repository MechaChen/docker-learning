FROM node:21-bullseye

WORKDIR /my-blog

COPY package.json .

RUN yarn install

COPY . .

EXPOSE 5173

CMD ["yarn", "run", "dev"]

