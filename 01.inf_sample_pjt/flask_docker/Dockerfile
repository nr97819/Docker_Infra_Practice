FROM python:3.9-alpine

WORKDIR usr/src/flask_app
COPY requirements.txt .
RUN pip install -r requirements.txt #-r 옵션은 파일(requirement.txt)에 적혀있는 라이브러리를 설치하라는 의미
COPY ./flask_app .
