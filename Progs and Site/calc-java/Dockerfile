FROM openjdk:latest 

LABEL version="1.3" 

WORKDIR /calcs 

COPY calc.java /calcs/

RUN javac calc.java

CMD ["java", "calc"]