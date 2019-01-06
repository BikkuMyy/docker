FROM ubuntu:16.04 

WORKDIR /mydir
COPY curler.sh .
RUN apt-get update && apt-get install -y curl
CMD ["/bin/bash", "curler.sh", "start"]