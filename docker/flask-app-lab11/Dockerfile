
FROM python:3.9-slim

ENV APP_MODE=production
ENV APP_REGION=canada-west

WORKDIR /app

COPY . /app

RUN pip install flask

EXPOSE 8080

CMD ["python", "Docker-3/app.py"]


