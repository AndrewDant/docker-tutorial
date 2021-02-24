# use an existing image as a base
FROM alpine

# download and install some dependencies
RUN apk add --update redis

# tell image what to do on container startup
CMD ["redis-server"]