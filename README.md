Gradle - Spring 4 MVC Hello World
===============================
Template for Spring 4 MVC + JSP view + XML configuration, using Gradle build tool.

###1. Technologies used
* Gradle 2.0
* Spring 4.1.6.RELEASE
* JSTL 1.2
* Logback 1.1.3
* Boostrap 3

###2. To Run this project locally
```shell
$ git clone https://github.com/mkyong/spring4-mvc-gradle-xml-hello-world
$ gradle jettyRun
```
Access ```http://localhost:8080/spring4```

###3. To import this project into IDEA IDE
1. ```$ gradle idea```
2. Open the project directly
3. Done.

###4. To debug this project from IDEA IDE
1. configure the remote, set the port 9999
2. Start jetty with jvm setting
gradle jR -Dorg.gradle.jvmargs="-Xmx2048m -XX:MaxPermSize=512m -XX:+HeapDumpOnOutOfMemoryError -Dfile.encoding=UTF-8 -Xdebug -Xrunjdwp:transport=dt_socket,address=9999,server=y,suspend=n"
3. click debug from IDEA
Connected to the target VM, address: 'localhost:9999', transport: 'socket'
4. with breakpoint, you can debug the code
5. http://blog.csdn.net/huijianpang/article/details/51516749




