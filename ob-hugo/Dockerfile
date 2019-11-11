FROM registry.hub.docker.com/library/fedora:latest
MAINTAINER https://openblox.org

RUN dnf -y update && dnf clean all
RUN dnf -y install findutils git hugo tidy doxygen perl perl-XML-LibXML && dnf clean all
