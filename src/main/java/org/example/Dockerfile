FROM alpine
RUN apk add openjdk17
WORKDIR /app
COPY ./src/main/java/org/example /app
CMD ["java", "Main.java"]