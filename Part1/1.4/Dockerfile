FROM ubuntu:16.04

RUN apt-get update && apt-get install -y curl
CMD ["/bin/sh", "-c", "read website; sleep 3; curl http://$website;"]