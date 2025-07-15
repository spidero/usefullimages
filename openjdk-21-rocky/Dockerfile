FROM rockylinux/rockylinux:10-minimal

WORKDIR /tmp

RUN microdnf update -y  && microdnf install java-21-openjdk-devel -y  && microdnf clean all && rm -rf /var/cache/dnf 
