# Dockerfile , Image , Container
FROM python:3.9.1-alpine

ADD server.py .
ADD dashboard.html .

RUN pip install pygame

CMD ["python","./server.py"]
