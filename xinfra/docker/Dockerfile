FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
RUN addgroup -S istory && adduser -S istory -G istory
USER istory
WORKDIR /home/istory
RUN ls -al
COPY springbootdeveloper-0.0.1-SNAPSHOT.jar /home/istory/istory.jar
ENTRYPOINT ["java","-jar","/home/istory/istory.jar"]
