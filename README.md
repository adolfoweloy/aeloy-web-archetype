# Maven Archetype
This is aeloy-web-archetype which was created to ease the bootstrap process for building Maven based Java Web Applications.

## Features
The web application that will be created by this archetyp will have the following features:

* JDK version 1.7
* Servlet API 3.0
* JSP API 2.3
* JSTL 2.1
* JUnit 4.12

## usage
At first you need to clone this repository and run the following command locally to have this archetype installed.

```
cd aeloy-web-archetype
mvn install
```

So you can create switch from aeloy-web-archetype directory and start creating your maven based web project
```
mvn archetype:generate -DarchetypeGroupId=br.com.aeloy -DarchetypeArtifactId=aeloy-web-archetype -DarchetypeCatalog=local
```
