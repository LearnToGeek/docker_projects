# Use existing docker image as a base image
FROM alpine



# Downloading dependencies 
RUN apk add --update redis


# Telling docker image that what to run intitially
CMD ["redis-server"]
