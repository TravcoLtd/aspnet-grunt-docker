FROM registry.travco.co.uk/aspnet:1.0.0-beta8

WORKDIR /

RUN curl -sL https://deb.nodesource.com/setup | bash -
RUN apt-get install -y \
	nodejs \
	git

RUN npm install -g grunt-cli