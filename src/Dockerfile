FROM python:3.12-alpine3.20

WORKDIR /app

COPY ./requirements.txt /app/

RUN pip install -r requirements.txt

COPY ./app.py /app/

CMD ["flask", "run", "--host", "0.0.0.0"]