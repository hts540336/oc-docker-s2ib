# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

# CMD ["/bin/bash", "-c", "sleep infinity"]
# Changing Dockerfile parameters to generate new output in OCP pod
CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
