FROM nvcr.io/nvidia/l4t-tensorflow:r32.6.1-tf2.5-py3
RUN apt update
RUN apt install net-tools -y
RUN mkdir /worktmp
RUN echo "welcome to FPG" > /worktmp/message.txt
COPY app/* /worktmp
CMD ['/bin/bash', -c]
