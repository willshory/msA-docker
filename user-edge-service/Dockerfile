FROM hub.idig88.com:8888/micro-service/java:openjdk-8
MAINTAINER liming www.idig8.com

COPY target/user-edge-service-1.0-SNAPSHOT.jar /user-edge-service.jar

ENTRYPOINT ["java","-jar","/user-edge-service.jar"]