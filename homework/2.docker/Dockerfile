FROM python:3.10.5-slim-bullseye

COPY python /python

RUN pip install -r /python/requirements.txt

EXPOSE 8080

USER 8080

WORKDIR /python

CMD ["python3",  "app.py" ]