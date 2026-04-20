FROM almalinux:9
RUN dnf install nginx -y
#root access require to create user or install packages
RUN useradd roboshop

USER roboshop
CMD ["sleep", "100"]    
