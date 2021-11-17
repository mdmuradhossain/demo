FROM openjdk:11
MAINTAINER io.murad
COPY target/demo-0.0.1-SNAPSHOT.jar demo.jar
ENTRYPOINT ["java","-jar","/demo.jar"]

FROM jboss/wildfly
COPY demo-0.0.1-SNAPSHOT.jar /opt/jboss/wildfly/standalone/deployments/
