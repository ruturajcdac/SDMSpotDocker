FROM openjdk:17-jdk-slim

WORKDIR /app

COPY GreetUser.java .

RUN javac GreetUser.java

CMD ["java", "GreetUser", "$@"]
