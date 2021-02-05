# LABORATORY - CLIENTS AND SERVICES WORKSHOP. 🚀


## Escuela Colombiana de Ingeniería - Enterprise Architectures(AREP).

_This workshop presents different challenges that will help you explore the concepts of naming schemes and clients and services. Additionally, the workshop will help you explore the architecture of applications distributed over the internet._

##HEATING

#### EXERCISE 1
_Write a program in which you create a URL object and print each component of a URL to the screen. That is, you must use the following methods: getProtocol, getAuthority, getHost, getPort, getPath, getQuery, getFile, getRef. Make sure neither prints an empty string, this implies that the URL you use for your object must contain enough data._

#### EXERCISE 2
_Write a browser application that, given a URL, reads data from that address and stores it in a file with the name result.html. Try to view this file in the browser. Your implementation must be a program that receives the URL parameter via the command line._

#### EXERCISE 3
_Using sockets write a server that receives a number and answers the square of this number. Write a customer to test it and send him a sequence of 20 numbers._

### CHALLENGE 1
_Write a web server that supports multiple requests in a row (non-concurrent). The server should return all requested files, including html pages and images. Build a website with javascript to test your server. Deploy your solution on Heroku. DO NOT use web frameworks like Spark or Spring use only Java and the libraries for network management._

### CHALLENGE 2 (ADVANCED)
_Using your server and java (DO NOT use web frameworks like Spark or Spring). Write a Spark-like framework that allows you to publish "get" web services with lambda functions and allow you to access static resources such as pages, javascripts, images, and CSSs. Create an application that connects to a database from the server to test your solution. Deploy your solution on Heroku._

## Getting Started

### Prerequisites

- [Maven](https://maven.apache.org/) - Dependency Management.

- [Java 8](https://www.oracle.com/co/java/technologies/javase/javase-jdk8-downloads.html) -  Development Environment.

- [Git](https://git-scm.com/) - Version Control System.

Make sure you have this programs installed correctly and the version that we need with the following commands:

```
mvn --version
```

```
git --version
```

```
java -showversion
```

### Installing

1. Clone the repository:

```
git clone https://github.com/angiedanielar/LAB3_AREP.git
```

2. Compile the projet:

```
mvn package
```

3. Executing the program:

```
mvn exec:java -D "exec.mainClass"="edu.escuelaing.arep.---"

And put this link in your browser: http://localhost:36000/index.html
```

4. Generating the documentation:

```
mvn javadoc:javadoc
```

- [View Documentation Ubication](https://angiedanielar.github.io/LAB3_AREP/apidocs)

## Built With

- [Maven](https://maven.apache.org/) - Dependency Management

- [Java 8](https://www.oracle.com/co/java/technologies/javase/javase-jdk8-downloads.html) -  Development Environment.

- [Git](https://git-scm.com/) - Version Control System.

- [CircleCI](https://circleci.com/) [![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://app.circleci.com/pipelines/github/angiedanielar/LAB3_AREP) - Continuous Integration.

- [Latex](overleaf.com) - Text composition system.

- [Heroku](https://www.heroku.com/platform) - Deploy platform.

## Inform

- [View the Design Inform](https://github.com/angiedanielar/LAB3_AREP/blob/master/Inform.pdf)

## Author

- Angie Daniela Ruiz Alfonso.


## License

This project is under GNU General Public License - see the [LICENSE](LICENSE) file for details.