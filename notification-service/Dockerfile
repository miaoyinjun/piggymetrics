FROM goodrainapps/maven:jdk8-alpine
MAINTAINER guox <guox@goodrain.com>

# Caching Maven dependencies
WORKDIR /app

# package
COPY . /app

CMD ["java", "-Xmx200m", "-jar", "/app/target/notification-service.jar"]

EXPOSE 8000
