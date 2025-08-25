FROM python:3.11-alpine

RUN mkdir /build
WORKDIR /build

COPY app /build

COPY app/requirements.txt /build

RUN pip install -r requirements.txt

EXPOSE 5000

CMD [ "python", "app.py" ]