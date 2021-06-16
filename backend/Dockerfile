FROM node:14.16.0

ENV PATH /app/node_modules/.bin:$PATH

COPY . ./

RUN npm install --silent

CMD ["npm", "start"]