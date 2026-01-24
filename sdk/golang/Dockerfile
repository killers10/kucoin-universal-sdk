FROM golang:1.26rc2

WORKDIR /app
RUN apt-get update && apt-get install -y bash
COPY . /src
COPY script/* /app/
COPY example/* /app/
