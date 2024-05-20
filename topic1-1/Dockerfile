FROM gradle AS build

WORKDIR /app

COPY . .

RUN gradle build --no-daemon

FROM eclipse-temurin:17-jdk-alpine AS run

WORKDIR /app

COPY --from=build /app/build/libs/*.jar app.jar

CMD ["java", "-jar", "app.jar"]