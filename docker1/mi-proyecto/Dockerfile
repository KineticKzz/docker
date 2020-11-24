FROM debian
RUN apt-get update && apt-get -y install cowsay
ENV PATH="$PATH:/usr/games"
ENTRYPOINT ["cowsay"]
CMD ["hola"]
