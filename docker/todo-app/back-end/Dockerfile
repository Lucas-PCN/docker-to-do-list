FROM node:14-alpine AS todobackend
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 3001
CMD [ "npm", "start" ]
