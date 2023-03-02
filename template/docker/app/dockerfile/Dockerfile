FROM tomcat:9.0.72-jdk17

MAINTAINER nhattien.lam.545@gmail.com
RUN apt update -y
COPY $package_file /usr/local/tomcat/webapps/$package_file

WORKDIR /usr/local/tomcat/bin

CMD ["catalina.sh", "run"]