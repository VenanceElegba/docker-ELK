FROM docker.elastic.co/beats/filebeat:7.5.1
COPY filebeat.yml /usr/share/filebeat/filebeat.yml
USER root
#RUN chown root:filebeat /usr/share/filebeat/filebeat.yml && 
RUN mkdir -p /usr/share/filebeat/kannel_logs && chmod -Rv 777 /usr/share/filebeat/kannel_logs
#USER filebeat
USER root