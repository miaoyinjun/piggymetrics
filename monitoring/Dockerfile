FROM java:8-jre
MAINTAINER Alexander Lukyanchikov <sqshq@sqshq.com>

COPY ./target/monitoring.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/monitoring.jar"]

EXPOSE 8080