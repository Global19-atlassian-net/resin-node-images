FROM resin/rpi-node:0.10.27

RUN mkdir -p /app
WORKDIR /app

ONBUILD COPY . /app
ONBUILD RUN npm install --unsafe-perm

CMD [ "npm", "start" ]

