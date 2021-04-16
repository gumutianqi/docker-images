FROM quay.io/quarkus/centos-quarkus-maven:21.0-java11
USER root
RUN yum install -y gcc-c++ make
RUN yum install -y git zip unzip
USER quarkus
CMD [ "java --version" ]
