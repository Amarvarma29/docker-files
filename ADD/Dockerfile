FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/index.html
ADD https://github.com/Amarvarma29/docker-files /usr/share/nginx/html/index.html
# The ADD command is used to copy files from a URL 
CMD ["nginx", "-g", "daemon off;"]