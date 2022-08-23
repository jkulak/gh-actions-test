FROM python:3.10.2-alpine3.15

WORKDIR /app

ADD ./src/ ./

RUN pip install --no-cache-dir pipenv && \
    pipenv install

CMD [ "pipenv", "run", "python", "./test.py" ]
