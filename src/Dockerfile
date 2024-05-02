FROM mongo:7.0.9

RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y node
RUN npm install -g --silent faker
CMD ["mongod"]