<<<<<<< HEAD
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf  /usr/share/nginx/html/index.html
ADD  https://raw.githubusercontent.com/Ayesha086/dockerfiles/refs/heads/main/RUN/Dockerfile  /usr/share/nginx/html/index.html
RUN chmod  +x /usr/share/nginx/html/index.html
=======
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf  /usr/share/nginx/html/index.html
ADD  https://raw.githubusercontent.com/Ayesha086/dockerfiles/refs/heads/main/RUN/Dockerfile  /usr/share/nginx/html/index.html
>>>>>>> 1e9466daee1c95db0c8a28125ae945bc245f6c66
CMD  ["nginx", "-g", "daemon off;"] 