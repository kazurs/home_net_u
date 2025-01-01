FROM alpine:latest
ENV RSYSLOG_CONF=/etc/rsyslog.conf
EXPOSE 514
# VOLUME /etc/rsyslog.conf
RUN apk update && apk add rsyslog
CMD /usr/sbin/rsyslogd -n -f $RSYSLOG_CONF
