FROM ubuntu:20.04
RUN apt update
RUN apt install net-tools -y
RUN mkdir /worktmp
RUN echo "welcome to demo" > /worktmp/message.txt
COPY app/* /worktmp
CMD ['/bin/bash', -c]
