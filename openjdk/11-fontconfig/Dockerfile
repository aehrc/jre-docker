FROM alpine:latest

ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8

RUN apk add --update --no-cache \
  openjdk11-jre \
  tzdata \
  # Fix java.lang.UnsatisfiedLinkError: no fontmanager in java.library.path
  fontconfig ttf-dejavu

ENV JAVA_HOME=/usr/lib/jvm/java-11-openjdk
