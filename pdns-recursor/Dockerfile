FROM quay.io/cehoffman/pdns-base

COPY recursor.conf.tmpl /etc/confd/templates/
COPY recursor.toml /etc/confd/conf.d/
COPY entrypoint.sh /bin/

EXPOSE 53
EXPOSE 53/udp

ENTRYPOINT ["/bin/entrypoint.sh"]
