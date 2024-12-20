FROM    node:alpine
WORKDIR /usr/vinay
COPY ./package.json ./
RUN   npm  install
COPY ./ ./
CMD ["npm", "start"]