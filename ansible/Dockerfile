FROM ubuntu:18.04

ARG ANSIBLE_VERSION=2.9
RUN apt-get update
RUN apt-get dist-upgrade
RUN apt-get install software-properties-common
RUN apt-add-repository --yes --update ppa:ansible/ansible-${ANSIBLE_VERSION}
RUN apt-get install ansible
