FROM alpine
LABEL maintainer="Vfeelit <vfeelit@qq.com>"

RUN apk add --no-cache beanstalkd

EXPOSE 11300
ENTRYPOINT ["/usr/bin/beanstalkd"]
