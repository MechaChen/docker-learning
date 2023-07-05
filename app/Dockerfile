# build the parent Image to set up language environment
FROM node:20-alpine

# the Image, container work directory
WORKDIR /app

# copy the current directory to image work directory
COPY . .

# run instruction in the Image work directory to set up environment
RUN yarn install

EXPOSE 4000

# command to be execute by Container (Docker process)
CMD ["node", "app.js"]


## cd app
# go to the app directory


## docker build -t my-docker-app .
# build the image with tag(name) in the current directory