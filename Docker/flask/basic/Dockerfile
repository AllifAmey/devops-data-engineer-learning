FROM python:alpine3.19

LABEL maintainer="Flaskboy"

WORKDIR /app

COPY . /app

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python3","hello.py"]
