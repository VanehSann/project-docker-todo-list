FROM node:14-alpine AS build
WORKDIR /app
COPY . .
ENTRYPOINT [ "npm", "install" ] && [ "npm", "test" ]
ADD node_modules.tar.gz .
EXPOSE 3001
CMD [ "npm", "start" ]
