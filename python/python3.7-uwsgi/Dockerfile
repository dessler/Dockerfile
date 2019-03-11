FROM python:3.7
RUN apt-get update && apt-get install vim tcpdump -y && pip install uwsgi
RUN apt-get clean && apt-get -y update && apt-get install -y locales
RUN sed -i 's/^# *\(en_US.UTF-8\)/\1/' /etc/locale.gen && locale-gen locale-gen en_US.UTF-8
