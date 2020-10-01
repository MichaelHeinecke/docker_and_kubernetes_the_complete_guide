# Use existing docker image as base
FROM alpine

# Download and install a dependency
RUN apk add --update gcc
RUN apk add --update redis

# Commands to be run on start-up
CMD ["redis-server"]
