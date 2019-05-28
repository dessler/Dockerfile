FROM centos:7.6.1810
MAINTAINER chenhong dan.dessler@163.com
ADD jdk1.8.0_181 /usr/local/jdk1.8.0_181
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
RUN echo 'Asia/Shanghai' >/etc/timezone
ENV LANG en_US.UTF-8
ENV JAVA_HOME /usr/local/jdk1.8.0_181
ENV PATH /usr/local/sbin:/usr/local/bin:/sbin:/bin:/usr/sbin:/usr/bin:/root/bin:$JAVA_HOME/bin
