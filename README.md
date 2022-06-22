-- run jar file for remote debug connection

java **-agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=*:5005** -jar spring-simplresponse-0.0.1-SNAPSHOT.jar
