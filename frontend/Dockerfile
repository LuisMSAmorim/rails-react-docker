FROM node:16.0.0

WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

COPY package.json /app/package.json

RUN npm install 

COPY . .

EXPOSE 5001

CMD ["npm", "run", "dev"]