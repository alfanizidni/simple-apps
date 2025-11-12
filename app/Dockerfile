From node:18.16
RUN apt update -y
WORKDIR /app
ADD . /app
RUN npm install
LABEL author="alfani.z.hidayah@mu.co.id"
CMD ["npm", "start"]