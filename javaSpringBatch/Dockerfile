FROM openjdk:8
ADD target/docker-springb-boot.jar docker-springb-boot.jar
EXPOSE 8085
ENTRYPOINT ["java","-jar","docker-springb-boot.jar"]