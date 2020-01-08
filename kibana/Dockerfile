ARG ELK_VERSION

# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/kibana/kibana:${ELK_VERSION}
#USER root
# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>
## Install elastalert using this doc : https://elastalert.readthedocs.io/en/latest/running_elastalert.html
#Pre-requis Python 2.7
#RUN yum update && yum install -y gcc openssl-devel bzip2-devel make wget
#WORKDIR /usr/src/
#RUN wget https://www.python.org/ftp/python/2.7.16/Python-2.7.16.tgz && \
#tar xzf Python-2.7.16.tgz
#WORKDIR /usr/src/Python-2.7.16
#RUN ./configure --enable-optimizations && make altinstall && \
#curl "https://bootstrap.pypa.io/get-pip.py" -o "get-pip.py" && \
#/usr/bin/python /usr/bin/python2.7 get-pip.py
#COPY ./config.yaml.example /usr/src/Python-2.7.16/config.yaml
