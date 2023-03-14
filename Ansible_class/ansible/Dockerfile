FROM project42/ubuntu-ssh-server:latest

RUN apt-get update
RUN apt-get install vim -y
RUN rm -f /set_root_pw.sh
RUN echo "root:pass" | chpasswd
