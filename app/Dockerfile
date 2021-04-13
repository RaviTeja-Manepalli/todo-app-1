FROM maven:3.5-jdk-8
# COPY ./ ./maven-app
# WORKDIR /maven-app 
# RUN mvn package -Dmaven.test.skip=true

COPY **/TodoDemo-0.0.1-SNAPSHOT.war app.war
ENTRYPOINT [ "java","-jar","app.war" ]
