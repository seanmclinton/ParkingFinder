FROM azul/zulu-openjdk:17-latest
VOLUME /tmp
COPY build/libs/*.jar app.jar
ENTRYPOINT [ "java", "-jar", "/app.jar"]

# docker build -t parkingfinder .
# docker run -p 8080:8080 parkingfinder