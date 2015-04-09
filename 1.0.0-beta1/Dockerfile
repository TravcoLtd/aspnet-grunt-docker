FROM microsoft:aspnet-docker:1.0.0-beta1

WORKDIR /

RUN curl -sL https://deb.nodesource.com/setup | bash -
RUN apt-get update
RUN apt-get install -y nodejs
RUN npm install -g grunt-cli