FROM alpine
MAINTAINER Ciel <me@ciel.im>

RUN apk --update add \
	curl wget perl python git bash zsh vim jq
RUN curl -sSL dot.ciel.im | bash

CMD ["zsh"]
