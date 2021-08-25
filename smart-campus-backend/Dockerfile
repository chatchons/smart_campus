# we will use openjdk 16 with alpine as it is a very small linux distro
FROM openjdk:16

# copy the packaged jar file into our docker image
COPY ./SMART_CAMPUS_BACKEND-0.0.1-SNAPSHOT.jar /SMART_CAMPUS_BACKEND-0.0.1-SNAPSHOT.jar

# set the startup command to execute the jar
CMD ["java", "-jar", "/SMART_CAMPUS_BACKEND-0.0.1-SNAPSHOT.jar"]
