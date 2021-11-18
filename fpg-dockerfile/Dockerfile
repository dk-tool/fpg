FROM nvcr.io/nvidia/tensorflow:21.10-tf1-py3
RUN apt update
RUN apt install net-tools -y
RUN mkdir /worktmp
RUN echo "welcome to demo" > /worktmp/message.txt
CMD ['/bin/bash', -c]
