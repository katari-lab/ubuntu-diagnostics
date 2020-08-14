from ubuntu:20.10

USER root
RUN apt-get update -y 
RUN apt-get upgrade -y 
RUN apt-get install dnsutils -y
RUN apt-get install iputils-ping -y
RUN apt-get install curl -y
RUN apt-get update -y 
RUN apt install software-properties-common -y 
RUN add-apt-repository ppa:deadsnakes/ppa
RUN apt install python3.8 -y 
RUN apt install python3-pip -y
RUN apt-get install vim -y
RUN python3 --version
RUN echo 'root:diag!' | chpasswd