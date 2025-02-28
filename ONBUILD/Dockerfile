FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/html/index.html
COPY INDEX.HTML  /usr/share/html/index.html
ONBUILD  