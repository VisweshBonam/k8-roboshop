FROM almalinux:9
# telnet --> telnet
# net-tools --> ifconfig, netstat, route, arphostname
# iputils --> ping
RUN dnf install telnet net-tools iputils -y
RUN useradd roboshop
USER roboshop
CMD ["sleep" , "1000000"]