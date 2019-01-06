FROM ubuntu:16.04 

WORKDIR /mydir
RUN apt-get update && apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs
EXPOSE 5000
CMD ["/bin/bash", "exposer.sh", "start"]