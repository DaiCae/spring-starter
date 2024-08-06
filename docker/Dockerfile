FROM mcr.microsoft.com/openjdk/jdk:17-distroless

WORKDIR /app
COPY start-site-exec.jar /app/starter.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "starter.jar"]