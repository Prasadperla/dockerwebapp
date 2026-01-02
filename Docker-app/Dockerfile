FROM tomcat:8-jre11

RUN rm -rf /usr/local/tomcat/webapps/*

copy target/vprofile-v2.war /var/lib/jenkins/workspace/Pipeline/

COPY vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]

