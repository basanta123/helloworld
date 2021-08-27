HelloWorld
==========

A simple Java application that can be compiled into a .jar file using Maven.

To build
--------
    mvn clean package (This only works from outside the jenkins for jenkins mvn is not needed in this command)

To run
------
    java -cp target/helloworld-1.0.jar com.coveros.demo.helloworld.HelloWorld
