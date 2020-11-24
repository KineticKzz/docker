FROM debian:latest
RUN apt-get update && apt-get install -y cowsay
ENV PATH="$PATH:/usr/games"
ENTRYPOINT ["cowsay"]
CMD ["hola"]
