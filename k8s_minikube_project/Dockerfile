FROM postman/newman:alpine

RUN npm install -g newman-reporter-influxdb

WORKDIR /etc/newman

COPY . ./

ENTRYPOINT ["newman"]