FROM node:alpine 
# was node:8

WORKDIR /app
COPY . ./

RUN npm install 
#--silent

EXPOSE 3000

CMD ["npm", "start"]