FROM alpine:3.10.2
LABEL description="Custom Alpine-Node Image"
MAINTAINER Daniele Tori
RUN addgroup -S node && \ 
    adduser -S -G node node && \
    apk --no-cache add nodejs 
USER node
EXPOSE 8081
COPY ./main.js /home/node/
CMD ["node", "/home/node/main.js"]  
