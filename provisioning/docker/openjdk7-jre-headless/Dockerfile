# Installs Headless OpenJDK JRE 7 on top of Ubuntu Precise64.
FROM stackbrew/ubuntu:raring
MAINTAINER Steven Swor "https://github.com/sworisbreathing"

# Install OpenJDK JRE 7 Headless
RUN apt-get -y --force-yes install openjdk-7-jre-headless && apt-get clean
# Set JAVA_HOME
RUN update-alternatives --display java
RUN echo "JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64" >> /etc/environment
