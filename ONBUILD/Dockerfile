FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# onbuild instruction will executes if any useer will uses your image as base os
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g","daemon off;" ]