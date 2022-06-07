FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app
# COPY . .
# RUN npm install
ADD node_modules.tar.gz .
COPY . .
# EXPOSE 3001
CMD [ "npm", "test" ]
