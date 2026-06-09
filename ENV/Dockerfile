FROM almalinux:9
ENV MONGO_URL="mongodb-dev.daws88c.online" \
RUN dnf install nginx -y
EXPOSE 80
CMD ["nginx","-g","daemon off;"]