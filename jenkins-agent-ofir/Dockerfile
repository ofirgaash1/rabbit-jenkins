FROM jenkins/inbound-agent:latest-jdk17

USER root

RUN apt-get update && \
    apt-get install -y curl docker.io docker-compose && \
    apt-get clean

USER jenkins

