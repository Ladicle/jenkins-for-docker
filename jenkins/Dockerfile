FROM jenkins:2.3-alpine

# Install plugins
COPY plugins.txt /usr/share/jenkins/plugins.txt
RUN /usr/local/bin/plugins.sh \
        /usr/share/jenkins/plugins.txt
