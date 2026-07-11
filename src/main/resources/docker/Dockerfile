FROM openjdk:17-jdk-slim
WORKDIR /opt/solo
COPY build/libs/solo-blog-*.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]
