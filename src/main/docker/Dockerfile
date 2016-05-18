FROM java:8

ADD @project.build.finalName@.jar /prueba.jar
RUN bash -c 'touch /prueba.jar'

# ---------- Container ---------------
EXPOSE 8089
ENTRYPOINT /usr/bin/java -jar /prueba.jar

