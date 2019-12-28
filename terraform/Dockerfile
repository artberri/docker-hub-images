FROM ubuntu:18.04

ARG TERRAFORM_VERSION=latest
RUN apt-get update
RUN apt-get dist-upgrade
RUN apt-get install -y curl bash unzip
RUN curl -o /tmp/terraform.zip https://releases.hashicorp.com/terraform/${TERRAFORM_VERSION}/terraform_${TERRAFORM_VERSION}_linux_amd64.zip
RUN unzip /tmp/terraform.zip -d /usr/bin/
