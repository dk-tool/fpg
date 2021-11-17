FROM example-registry-quay-quay-test.apps.ocp4.nh.com/sti/fpg:tf19.10-py3
RUN echo nameserver 8.8.8.8 >> /etc/resolv.conf
RUN apt update
CMD ['/bin/bash', -c]
