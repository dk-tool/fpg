FROM example-registry-quay-quay-test.apps.ocp4.nh.com/sti/fpg:tf19.10-py3
RUN apt update
RUN apt install net-tools -y
RUN mkdir /worktmp
RUN echo "welcome to demo" > /worktmp/message.txt
CMD ['/bin/bash', -c]
