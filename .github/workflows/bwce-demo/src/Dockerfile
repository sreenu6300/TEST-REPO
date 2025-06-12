FROM alpine:3.18

WORKDIR /opt/tibco

COPY main.sh /opt/tibco/
COPY app-docker.properties /opt/tibco/config/

RUN chmod +x /opt/tibco/main.sh

CMD ["/opt/tibco/main.sh"]
