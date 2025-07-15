FROM rockylinux/rockylinux:9-minimal

WORKDIR /tmp

RUN microdnf update -y  && microdnf install java-17-openjdk-devel -y  && microdnf clean all && rm -rf /var/cache/dnf 
