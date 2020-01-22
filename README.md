# STARTER-lab02
# Heroku deploy is under https://cs56-w20-tristanhernandez-lab2.herokuapp.com, and NOT https://cs56-w20-tristanhernandez-lab02.herokuapp.com due to space limitations

Javadoc: https://ucsb-cs56-w20.github.io/lab02-tristanhernandez-cs56
Repo: https://ucsb-cs56-w20/lab02-tristanhernandez-cs56

# About this repo

This is a minimal "Hello World" type webapp built with Spring Boot.


# Sources

The code in this repo is based in part on the tutorial here:
<https://spring.io/guides/gs/spring-boot/>, and the code here in the
`complete` directory of this repo
<https://github.com/spring-guides/gs-spring-boot.git>.  It has been
modified for use in UCSB CMPSC 56.

# What can you do with this code?

| Command | What it does   |
|----------|---------------------------------------|
| `mvn compile` | Should result in a clean compile |
| `mvn test` | Runs one sucessful test |
| `mvn package` | Builds the jar file `target/gs-spring-boot-0.1.0.jar` |
| `java -jar target/gs-spring-boot-0.1.0.jar` | If done after `mvn package`, runs the code to startup a web server.  Access it via `http://localhost:8080` on the *same machine* where the server is running.  Use CTRL/C to stop it. |

