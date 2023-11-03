#fully configured node image here expecting nodejs environment intalled alredy here.
FROM node:14
#all aplications opened at 8080
EXPOSE 8080
WORKDIR /opt/server
COPY package.json .
# . means current directory
COPY sever.js .
RUN npm install
CMD ["nodejs", "nodejs"]


