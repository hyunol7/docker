# 베이스 이미지

FROM ubuntu:latest

RUN apt update
RUN apt install nginx -y 
#무조건 yes -y

RUN echo "<h1>Hello World</h1>" > index.html

CMD ["nginx", "-g daemon off;"]



