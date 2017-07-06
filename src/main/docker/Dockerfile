FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD infra-eureka-0.0.1-SNAPSHOT.jar infra-eureka.jar
RUN sh -c 'touch /infra-eureka.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar /infra-eureka.jar" ]