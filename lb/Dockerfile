FROM haproxy:1.7
RUN groupadd haproxy && useradd -g haproxy haproxy
COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg
EXPOSE 80