FROM node:alpine

WORKDIR /usr/app

# copy from path on local machine relative to build context
# to path in container
COPY ./package.json .
RUN npm config set registry http://registry.npmjs.org/
RUN npm install
COPY . .

CMD ["npm", "start"]
