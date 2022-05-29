FROM node:14-alpine AS build
WORKDIR /app
COPY . .
RUN npm install
# ADD node_modules.tar.gz .
EXPOSE 3001
ENTRYPOINT [ "npm", "test" ]
