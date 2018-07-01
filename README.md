# javahttpserv
Java 10 Simple HTTP Serv

## Check java version

~~~
java --version

java 10.0.1 2018-04-17
Java(TM) SE Runtime Environment 18.3 (build 10.0.1+10)
Java HotSpot(TM) 64-Bit Server VM 18.3 (build 10.0.1+10, mixed mode)
~~~

~~~
javac --version

javac 10.0.1
~~~

## Very very basic HelloWorld project

First step is to understand module, jlink...to be able to build an App 
suitable for microservices, IOT and Kubernetes

Get into the simplistic application directory
~~~
cd app1
~~~

Verify the presence of the source code
~~~
ls src/app1

HelloWorld.java
~~~

Compile the source java code
~~~
javac -d classes src/app1/*.java
~~~

Check javac call worked
~~~
ls classes/app1/

HelloWorld.class
~~~

Let's run the simplistic application using the classical way
~~~
java --class-path classes app1.HelloWorld

Hello World
~~~

