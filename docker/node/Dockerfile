FROM node:alpine

RUN apk update \
    && apk add --no-cache --virtual bash \
    && apk add vim

CMD ["npm", "install"]
CMD ["npm", "start"]
