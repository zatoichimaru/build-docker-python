FROM python:3.8-alpine

WORKDIR /usr/src/app

RUN apk add --no-cache gcc musl-dev linux-headers

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .
