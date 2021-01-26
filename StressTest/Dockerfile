FROM ubuntu
RUN apt-get update
RUN apt-get install -y stress-ng
RUN apt-get install -y sysbench
COPY entrypoint_test.sh /
RUN chmod u+x entrypoint_test.sh
CMD ["/bin/bash"]