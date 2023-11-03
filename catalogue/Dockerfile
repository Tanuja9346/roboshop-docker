#fully configured node image here expecting nodejs environment intalled alredy here.
FROM node:14
#all aplications opened at 8080
EXPOSE 8080
WORKDIR /opt/server
COPY package.json .
# . means current directory
COPY server.js .
RUN npm install
ENV MONGO=true
CMD ["node", "server.js"]


