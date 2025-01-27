FROM rockylinux:9
WORKDIR /
RUN yum clean all
RUN yum -y install dnsmasq
COPY ./dnsmasq.conf /etc/dnsmasq.conf
ENTRYPOINT ["dnsmasq", "-kC/etc/dnsmasq.conf"]
