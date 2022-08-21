FROM node:16

RUN apt-get update && apt-get install -y

WORKDIR /usr/src

COPY . /usr/src

EXPOSE 5000

RUN npm i
RUN npm run build

CMD ["npm", "start"]
