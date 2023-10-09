FROM openjdk:latest

LABEL version="1.3"

WORKDIR /game

COPY game.java /game/

RUN javac game.java

CMD ["java", "game"]
