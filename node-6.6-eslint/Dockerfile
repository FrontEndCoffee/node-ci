FROM mhart/alpine-node:6.6.0

MAINTAINER Jesse Kramer <jkramer@pcextreme.nl>

RUN npm install -g eslint@3.5.0
run mkdir /src
WORKDIR /src
ENTRYPOINT ["eslint"]
