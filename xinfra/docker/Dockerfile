FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
RUN addgroup -S istory && adduser -S istory -G istory
USER istory
WORKDIR /app
RUN ls -al
COPY *.jar /home/istory/istory.jar
ENTRYPOINT ["java","-jar","/home/istory/istory.jar"]
