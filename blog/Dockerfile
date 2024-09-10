FROM arm64v8/eclipse-temurin:17-jdk-focal

ARG JAR_FILE=build/libs/*.jar

COPY ${JAR_FILE} app.jar

ENTRYPOINT ["java", "-jar", "-Dusser.timezone=Asia/Seoul","/app.jar"]