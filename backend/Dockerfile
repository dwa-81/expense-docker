FROM node:20
EXPOSE 8080
ENV DB_HOST="mysql"
RUN mkdir /opt/server
WORKDIR /opt/server
COPY package.json .
copy *.js .
COPY schema .
RUN npm install
CMD ["node" , "index.js"]
