FROM node

WORKDIR /app

COPY . .

# This step can be skipped because of copy all content needed to run from source PC.
RUN npm install

EXPOSE $PORT

# node server.js
ENTRYPOINT ["node", "server.js"]