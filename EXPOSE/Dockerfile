FROM almalinux:9
RUN dnf install nginx -y
# container opening port, its just for information purpose. No functionality will work with EXPOSE
EXPOSE 80  
CMD ["nginx", "-g", "daemon off;"]