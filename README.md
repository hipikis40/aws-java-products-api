# Serverless REST API in Java/Maven using DynamoDB


## Install Pre-requisites

* `node` e `npm`
* Instalar a JDK e não a Java JRE da [Oracle JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html).
`export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk-10.jdk/Contents/Home`
* [Apache Maven](https://maven.apache.org/). After [downloading](https://maven.apache.org/download.html) e [installing](https://maven.apache.org/install.html) Apache Maven, adicione `apache-maven-x.x.x` ao `PATH` do windows.


Testa Java instalação:

```
$ java --version

java 10 2018-03-20
Java(TM) SE Runtime Environment 18.3 (build 10+46)
Java HotSpot(TM) 64-Bit Server VM 18.3 (build 10+46, mixed mode)
```

Testar Maven instalação:

```
$ mvn -v

Apache Maven 3.5.3 (3383c37e1f9e9b3bc3df5050c29c8aff9f295297; 2018-02-24T14:49:05-05:00)
Maven home: /usr/local/apache-maven-3.5.3
Java version: 10, vendor: Oracle Corporation
Java home: /Library/Java/JavaVirtualMachines/jdk-10.jdk/Contents/Home
Default locale: en_US, platform encoding: UTF-8
OS name: "mac os x", version: "10.13.3", arch: "x86_64", family: "mac"
```

## Build o projero Java

Crie o .jar (jar):

```
$ cd aws-java-products-api
$ mvn clean install
