FROM ubuntu:16.04
COPY setup.sh /tmp/
RUN bash /tmp/setup.sh
ENTRYPOINT chmod 777 /var/www/openeclass && exec /usr/sbin/apache2ctl -D FOREGROUND