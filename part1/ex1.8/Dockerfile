FROM ubuntu:16.04 

WORKDIR /mydir
RUN apt-get update && apt-get install -y default-jre curl
RUN curl -L https://github.com/BikkuMyy/tiralabra/blob/master/tiralabra.jar -o tiralabra.jar
RUN java -jar tiralabra.jar
CMD ["/bin/bash"]