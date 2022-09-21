FROM openjdk:8
LABEL maintainer="vidya.sagar"
EXPOSE 8083
ADD target/tweet_app-0.0.1-SNAPSHOT.jar tweet_app-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/tweet_app.jar"]