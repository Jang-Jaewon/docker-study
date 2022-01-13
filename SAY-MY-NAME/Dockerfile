# cenos 7버전의 이미지를 사용하겠다.
FROM centos:7

# name.txt를 root 디렉토리에 복사해 가져가겠다.
COPY name.txt .

# 3초 동안 sleep 했다가, 다시 cat name.txt를 명령하고, 이를 계속 반복
CMD while ture; do sleep 3; cat name.txt; done;