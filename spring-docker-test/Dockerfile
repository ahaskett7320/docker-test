FROM java:8
EXPOSE 9090:9090
ADD /out/artifacts/spring_docker_test_jar/spring-docker-test.jar spring-docker-test.jar
ENTRYPOINT ["java", "-jar", "spring-docker-test.jar" ]