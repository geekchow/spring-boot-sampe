# Read Me First
The following was discovered as part of building this project:

* The original package name 'geekchow.spring.web-demo' is invalid and this project uses 'geekchow.spring.webdemo' instead.

# Getting Started

Start the netty server host current project.
```shell
./gradlew bootRun
```

access the website via `http://localhost:8080/index.htm`


Test the api hello

```shell

curl --location --request GET 'http://localhost:8080/hello' 
```


### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.7.10/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.7.10/gradle-plugin/reference/html/#build-image)
* [Spring Reactive Web](https://docs.spring.io/spring-boot/docs/2.7.10/reference/htmlsingle/#web.reactive)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a Reactive RESTful Web Service](https://spring.io/guides/gs/reactive-rest-service/)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)

