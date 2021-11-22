# Using Alpine docker image latest version
FROM alpine

# Install python when building the docker image
RUN apk add python3

CMD [ "8.8.8.8" ]

# Ping 5 times the ip address pass in the CMD command
ENTRYPOINT [ "ping", "-t", "5" ]