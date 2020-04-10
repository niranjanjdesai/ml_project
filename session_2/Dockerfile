FROM ubuntu:18.04

RUN apt update

ENV DEBIAN_FRONTEND=noninteractive

RUN apt install -y python3 python3-pip

RUN pip3 install numpy scipy pandas matplotlib sklearn

RUN pip3 install jupyter

RUN apt install net-tools

CMD ["bash"]
