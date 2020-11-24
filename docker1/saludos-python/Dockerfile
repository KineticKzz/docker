FROM debian:latest
RUN apt-get update && apt-get install -y python3
WORKDIR /usr/mis-apps
ADD mis-apps .
ENTRYPOINT ["python3"]
CMD ["hola.py"]
