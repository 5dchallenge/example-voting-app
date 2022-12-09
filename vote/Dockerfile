FROM python:3.8.16-slim

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

EXPOSE 80

CMD  gunicorn app:app -b 0.0.0.0:80
