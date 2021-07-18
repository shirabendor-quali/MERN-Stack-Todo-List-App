FROM node:lts-alpine
RUN apk add curl
COPY . .
RUN npm install
ENV DB_URL host.docker.internal
EXPOSE 4000
CMD ["npm","start"]