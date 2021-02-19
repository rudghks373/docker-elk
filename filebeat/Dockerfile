FROM docker.elastic.co/beats/filebeat:7.11.0

COPY filebeat.yml /usr/share/filebeat/filebeat.yml
USER root

RUN mkdir /var/log/server
RUN chown -R root /usr/share/filebeat