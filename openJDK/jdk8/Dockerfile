FROM ubuntu:16.04
MAINTAINER suzp1984@gmail.com
RUN apt-get update && apt-get install -y build-essential libtool autotools-dev automake libasound2-dev libfreetype6-dev libcups2-dev libxrender-dev unzip cpio zip gawk procps file openjdk-8-jdk libx11-dev libxext-dev libxtst-dev libxt-dev libfreetype6
COPY openjdk-8-src-b132-03_mar_2014.zip /tmp/
RUN unzip /tmp/openjdk-8-src-b132-03_mar_2014.zip -d /root/
RUN rm -rf /tmp/openjdk-8-src-b132-03_mar_2014.zip
RUN cd /root/openjdk && bash ./configure --with-freetype-include=/usr/include/freetype2/  --with-freetype-lib=/usr/lib/x86_64-linux-gnu/ && make all




