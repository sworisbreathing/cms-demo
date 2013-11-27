# Installs curl and magnolia.
FROM sworisbreathing/openjdk7-jre-headless
MAINTAINER Steven Swor "https://github.com/sworisbreathing"

# Install curl
RUN apt-get -y --force-yes install curl

# Create /app directory
RUN mkdir /app/

# Download and install Magnolia
RUN curl http://nexus.magnolia-cms.com/content/repositories/magnolia.public.releases/info/magnolia/magnolia-tomcat-bundle/5.1.2/magnolia-tomcat-bundle-5.1.2-tomcat-bundle.tar.gz | tar -xz -C /app/

