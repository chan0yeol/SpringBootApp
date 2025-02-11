FROM amazoncorretto:17
EXPOSE 8090
COPY target/*.war SpringBootApp.war
ENTRYPOINT ["java","-jar","SpringBootApp.war"]