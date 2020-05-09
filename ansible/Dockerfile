FROM centos:8

RUN yum update -y && yum install -y epel-release

RUN yum install -y ansible

VOLUME /etc/ansible

WORKDIR /etc/ansible