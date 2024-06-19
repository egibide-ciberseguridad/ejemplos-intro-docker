FROM debian:latest

RUN apt-get update -y
RUN apt-get install -y python3-pyfiglet

COPY . /app

WORKDIR /app

ENTRYPOINT ["python3"]
CMD ["app.py"]
