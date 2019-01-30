FROM tomcat:9.0

EXPOSE 8080/tcp

COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
COPY context.xml  /usr/local/tomcat/webapps/manager/META-INF/context.xml
COPY config.properties /usr/local/tomcat/conf/Catalina/cs_select/config.properties


