FROM alpine:latest

ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8

RUN apk --no-cache update && \
    apk --no-cache upgrade && \
    apk --no-cache add openjdk17-jre-headless tzdata

ENV JAVA_HOME=/usr/lib/jvm/java-17-openjdk