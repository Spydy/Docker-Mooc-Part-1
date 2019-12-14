FROM ubuntu:18.04

RUN apt update && apt -y upgrade
RUN apt install -y python3-pip
RUN apt install -y build-essential libssl-dev libffi-dev python3-dev
RUN apt install -y python3-venv
RUN apt install -y vim
RUN echo 'alias python=python3' >> ~/.bashrc
RUN mkdir home/workspace
WORKDIR /home
