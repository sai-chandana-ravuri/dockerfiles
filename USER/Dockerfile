FROM almalinux:9
RUN dnf install nginx -y
#CMD ["nginx", "-g", "daemon off;"]
#root access required to create user or install packages
RUN useradd roboshop 
USER roboshop
CMD ["sleep", "100"]