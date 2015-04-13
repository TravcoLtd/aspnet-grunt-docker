FROM muojp/aspnet-docker:latest

WORKDIR /

RUN curl -sL https://deb.nodesource.com/setup | bash -
RUN apt-get update
RUN apt-get install -y \
	nodejs \
	git

RUN npm install -g grunt-cli