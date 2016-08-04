FROM sforzando-docker-dockerv2-local.artifactoryonline.com/newrelic:8-jre

COPY @project.build.finalName@.jar /opt/build/

WORKDIR /opt/build

EXPOSE 8080

CMD ["-Xmx1g", "-jar", "@project.build.finalName@.jar"]
