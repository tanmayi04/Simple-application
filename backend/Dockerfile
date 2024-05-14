FROM node:21

WORKDIR /app
#code
COPY . .

RUN npm i

COPY .env.sample .env

#port
EXPOSE 5000

#App run
CMD ["npm", "start"]
