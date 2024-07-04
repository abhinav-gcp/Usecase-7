# tomcat/Dockerfile
FROM tomcat:9.0
COPY HelloWorldServlet.java /usr/local/tomcat/webapps/ROOT/WEB-INF/classes/
RUN apt-get update && \
    apt-get install -y default-jdk && \
    javac /usr/local/tomcat/webapps/ROOT/WEB-INF/classes/HelloWorldServlet.java
EXPOSE 8080

