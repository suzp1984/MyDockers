FROM ubuntu:16.04
MAINTAINER suzp1984@gmail.com
RUN apt-get update && apt-get install -y clang libpython2.7 libxml2
# RUN cd /tmp; wget https://swift.org/builds/swift-2.2.1-release/ubuntu1510/swift-2.2.1-RELEASE/swift-2.2.1-RELEASE-ubuntu15.10.tar.gz && tar xvf swift-2.2.1-RELEASE-ubuntu15.10.tar.gz
# COPY /opt/prog/hack/swift/swift-2.2.1-RELEASE-ubuntu15.10.tar.gz /tmp/
COPY swift-2.2.1-RELEASE-ubuntu15.10.tar.gz /tmp/
RUN tar xvf /tmp/swift-2.2.1-RELEASE-ubuntu15.10.tar.gz -C /root/
ENV PATH "$PATH:/root/swift-2.2.1-RELEASE-ubuntu15.10/usr/bin"
