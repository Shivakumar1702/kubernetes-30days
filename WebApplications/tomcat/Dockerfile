FROM tomcat:9.0.82-jre8
LABEL maintainedby="shivakumar"
RUN apt-get update -y
WORKDIR /usr/local/tomcat/
RUN cp -r webapps.dist/* webapps/
COPY ./app/target/app.war webapps/
EXPOSE 8080