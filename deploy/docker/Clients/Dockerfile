FROM tomcat:7-jre8 
COPY drop/* /usr/local/tomcat/webapps/ 
COPY drop/index.jsp /usr/local/tomcat/webapps/ROOT/index.jsp 
EXPOSE 8080 
ENTRYPOINT ["catalina.sh", "run"]