FROM openjdk:8-jdk-alpine

VOLUME /opt/tmp

ADD springboot-docker-1.0.0.jar springboot-docker.jar

ENV JAVA_OPTS=""

ENTRYPOINT exec java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /springboot-docker.jar