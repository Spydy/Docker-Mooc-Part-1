FROM ubuntu:16.04

WORKDIR /workspace
RUN apt-get update && apt-get upgrade -y && apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install -y nodejs

COPY . /workspace
EXPOSE 5000
ENV API_URL=http://localhost:8000

RUN npm install
CMD [ "npm", "start" ]
