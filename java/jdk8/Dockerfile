FROM alpine:latest
RUN apk --update add bash openjdk8-jre-base && \
      rm -rf /var/cache/apk/*
ENV JAVA_HOME /usr/lib/jvm/default-jvm
ENV PATH ${PATH}:${JAVA_HOME}/bin