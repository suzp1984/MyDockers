FROM ubuntu:16.04
MAINTAINER suzp1984@gmail.com
RUN apt-get update && apt-get install -y build-essential libtool autotools-dev automake checkinstall check git yasm libsodium18 libsodium-dev libopus-dev libvpx-dev pkg-config
RUN cd /tmp; git clone --depth 1 https://github.com/irungentoo/toxcore;
RUN cd /tmp/toxcore; autoreconf -i && ./configure && make &&  make install


