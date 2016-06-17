FROM jenkinsci/jenkins
MAINTAINER alexander.mclachlan@gmail.com
# Prep Jenkins Directorieos

USER root
RUN mkdir /var/log/jenkins
RUN mkdir /var/cache/jenkins
RUN chown -R jenkins:jenkins /var/log/jenkins
RUN chown -R jenkins:jenkins /var/cache/jenkins
USER jenkins

# Set Defaults
ENV JAVA_OPTS="-Xmx1024m"