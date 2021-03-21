# FROM python:3.7
FROM python:3.8

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

WORKDIR /YOUTUBE_API

COPY requirements.txt ./
RUN python -m pip install --upgrade pip setuptools
RUN pip install -r requirements.txt

#Copy project
COPY . ./

EXPOSE 8000