FROM openjdk:8
VOLUME /tmp
EXPOSE 8001
ADD ./target/springboot-servicio-productos-0.0.1-SNAPSHOT.jar config-server.jar 
ENTRYPOINT ["java", "-jar", "/config-server.jar"]