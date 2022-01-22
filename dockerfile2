# Base image
FROM node:current AS build


WORKDIR /usr/src/app
# Copy all file
COPY . ./server/brightfoxServer

# Go back to app dir
WORKDIR /usr/src/app/server/brightfoxServer/

# Start server
CMD yarn run server
EXPOSE 8655