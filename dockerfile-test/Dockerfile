# 베이스 이미지 지정
FROM httpd:alpine
# 작성자 라벨
LABEL maintainer="jewon119@gmail.com"
# COPY 명령어
COPY ./2022_DEV /usr/local/apache2/htdocs
# CMD 명령어
# CMD ["/bin/sh"]
# 
# ENTRYPOINT 명령어
ENTRYPOINT ["/bin/echo", "hello"]
#
# 이미지 생성 명령 : docker build --tag myweb .
# 컨테이너 생성 명령 : docker run -dit -p 9999:80 --name apacheweb myweb /bin/sh hi
