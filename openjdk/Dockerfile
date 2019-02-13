FROM ubuntu:latest
MAINTAINER woochul<crepers12@hanmail.net>

RUN apt-get update
RUN apt-get install nano
RUN apt-get install -y openjdk-8-jdk
RUN apt-get clean

ENV TERM=xterm

ENV JAVA_HOME=/usr/lib/jvm/java-8-open-jdk-amd64
ENV CLASSPATH=$JAVA_HOME/lib/*:.
ENV PATH=$PATH:$JAVA_HOME/bin