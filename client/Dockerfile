FROM node:14-alpine

# Prevent react app error
ENV CI=true

WORKDIR /app
COPY ./package.json ./
RUN npm i
COPY ./ ./

CMD ["npm", "start"]