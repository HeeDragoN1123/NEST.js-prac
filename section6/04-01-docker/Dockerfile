# 1. 운영체제 및 프로그램 설치(하나하나 입력하는 방식)
# FROM ubuntu:24.04

# RUN sudo apt install nodejs
# RUN sudo npm install install -g yarn

# 1. 운영체제 및 프로그램 설치(이미 리눅스, node, npm ,yarn까지)
FROM node:14

# 2. 내 컴퓨터에 있는 폴더나 파일을 도커 컴퓨터 안으로 복사하기
COPY ./index.js /index.js

# 3 도커 안에서 index.js 실행시키기 (run과 다르게 cmd는 한번밖에 못씀)
# RUN node index.js
CMD node index.js
