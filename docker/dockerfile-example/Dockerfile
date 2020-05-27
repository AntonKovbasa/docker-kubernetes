# use an exixsting docker image as a base
FROM alpine



# download and install a dependency
RUN apk add --update redis
RUN apk add --update tree



# tell the image what to do when it starts as a containder
CMD ["redis-server"]
