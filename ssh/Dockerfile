FROM alpine:latest
# install ssh-client and bash
RUN apk --no-cache add openssh-client bash
# example ssh usage to print version
ENTRYPOINT ["ssh", "-V"]
