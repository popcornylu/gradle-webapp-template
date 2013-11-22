gradle-webapp-template
======================

This is a very simple webapp template project, in which you can compile, run and test your webapp in one single command line.

In Linux/Mac

`./gradlew jettyRun`

In Windows

`gradlew.bat jettyRun`

And your webapp will run at 

`http://localhost:8080/gradle-webapp-template/hello`

Based on this template project, start to write your own code as you like ;)

##Prerequisite

* The only thing you should prepare is to set JAVA_HOME in your envirnoment.

* No Servlet container/server is required.
* Gradle is not necessary to be installed.

##Note
Because jettyRun is based on Jetty6, Servlet 3.0 and beyond does not support.

