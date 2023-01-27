FROM tomcat:8.0
COPY  /var/lib/jenkins/workspace/DockerImage/java-tomcat-sample-docker/target/java-tomcat-maven-example.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
