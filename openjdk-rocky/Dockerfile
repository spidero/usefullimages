FROM rockylinux/rockylinux:10

WORKDIR /tmp

RUN dnf update -y  && dnf install wget java-21-openjdk-devel -y  && dnf clean all && rm -rf /var/cache/dnf