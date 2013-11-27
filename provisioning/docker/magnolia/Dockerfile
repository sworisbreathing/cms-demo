# Starts Magnolia on port 8080.
FROM sworisbreathing/magnolia-base
MAINTAINER Steven Swor "https://github.com/sworisbreathing"

# Start Magnolia
EXPOSE 8080
ENTRYPOINT /app/magnolia-5.1.2/apache-tomcat-7.0.40/bin/magnolia_control.sh start && tail -f /app/magnolia-5.1.2/apache-tomcat-7.0.40/logs/catalina.out
