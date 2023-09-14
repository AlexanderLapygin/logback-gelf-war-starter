<div align="center">
    <a href="https://github.com/softspiders/softspiders">
      <img src="https://avatars.githubusercontent.com/u/47006425?v=4" width="100" height="100"/>
    </a>
</div> 

# Logback GELF in war starter

## Feature tags
- gelf
- java
- logback
- maven
- starter
- template
- war

---

## Direct ancestors
[- war](https://github.com/AlexanderLapygin/logback-gelf-starter/tree/main#readme)

---

## Author

[Alexander Lapygin](https://github.com/AlexanderLapygin) <<alexanderlapygin@gmail.com>>

---

## Requirements

- [Java](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Tomcat](https://tomcat.apache.org/download-10.cgi)

---

## Run

1) Build the WAR file by running the Maven command:

```sh
mvn clean package
```
2) Copy the resulting *springboot-war-helloworld.war* file to the *webapps* directory of your Tomcat server.

3) Start the Tomcat server by executing the appropriate startup script for your operating system. For example, run startup.sh (for Unix) or startup.bat (for Windows).

4) After Tomcat starts successfully, your application will be accessible at http://localhost:8080/springboot-war-helloworld/hello.

### License

Licensed under the [MIT license](./LICENSE)

---

[SOFTSPIDERS](https://github.com/softspiders/softspiders)
