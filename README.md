# SBE Micro service project



## Compile the application

To compile the application you need java JDK 17 version and apache maven 3.8.1+.



## Packaging and running the application

To compile project you need to execute this maven command :

````shell
mvn clean install
````

To launch checkstyle plugin : 

````shell
mvn checkstyle:check
````

To launch PMD plugin: 

````shell
mvn pmd:check
````

To launch Spotbugs plugin:

````shell
mvn spotbugs:check
````

To generate quality reports: 

````shell
mvn verify site
````




