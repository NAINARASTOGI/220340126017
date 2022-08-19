FROM node:alpine
WORKDIR /usr/nancy/subscriber
COPY subscriber.js /usr/nancy/subscriber/
RUN npm install mqtt
CMD ["node", "subscriber.js"]