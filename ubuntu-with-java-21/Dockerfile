FROM ubuntu:latest
RUN apt-get update
ADD https://download.oracle.com/java/21/latest/jdk-21_linux-x64_bin.tar.gz /opt/jdk/
WORKDIR /opt/jdk
RUN tar -xvzf jdk-21_linux-x64_bin.tar.gz
RUN rm -rf jdk-21_linux-x64_bin.tar.gz
WORKDIR /