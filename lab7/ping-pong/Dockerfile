FROM openjdk:8-jdk-slim
COPY PingPongDeikun.java  /
RUN javac PingPongDeikun.java
EXPOSE 8080
ENTRYPOINT ["java"]
CMD ["PingPongDeikun"]
