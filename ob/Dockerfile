FROM registry.hub.docker.com/library/fedora:latest
MAINTAINER https://openblox.org

RUN dnf -y update && dnf clean all
RUN dnf -y install git libtool autoconf automake autoconf-archive lua-devel enet-devel pugixml-devel v8-devel v8 bullet-devel irrlicht-devel libcurl-devel gcc gcc-c++ make && dnf clean all
RUN dnf -y install unzip doxygen qt5-devel && dnf clean all
