HelloWorld
==========

A simple Java application that can be compiled into a .jar file using Maven and this would be teiggered using webhook over jenkins.
Triggeres a java application,

To build
--------
    mvn clean package

To run
------
    java -cp target/helloworld-1.1.jar com.coveros.demo.helloworld.HelloWorld
