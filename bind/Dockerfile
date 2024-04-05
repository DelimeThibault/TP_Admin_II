FROM internetsystemsconsortium/bind9:9.18

EXPOSE 53/tcp
EXPOSE 53/udp

CMD ["/usr/sbin/named", "-g", "-c", "/etc/bind/named.conf", "-u", "bind"]