FROM almalinux:8
RUN yum install nginx -y
RUN echo "Hello World" > /usr/share/nginx/html/hello.html
ENTRYPOINT [ "nginx","-g","daemon off;" ]