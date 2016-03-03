# gradle

Install configure Gradle: URLs

https://spring.io/guides/gs/gradle/

https://docs.gradle.org/current/userguide/tutorial_using_tasks.html


https://docs.gradle.org/current/userguide/userguide.html

https://docs.gradle.org/current/userguide/war_plugin.html

Gradle Commands:

gradle -v -- Version

gradle tasks -- to see available tasks

gradle build  --- 
After a few seconds, "BUILD SUCCESSFUL" indicates that the build has completed.

To see the results of the build effort, take a look in the build folder. Therein you’ll find several directories, including these three notable folders:

classes. The project’s compiled .class files.
reports. Reports produced by the build (such as test reports).
libs. Assembled project libraries (usually JAR and/or WAR files).
The classes folder has .class files that are generated from compiling the Java code. Specifically, you should find HelloWorld.class and Greeter.class.

At this point, the project doesn’t have any library dependencies, so there’s nothing in the dependency_cache folder.

The reports folder should contain a report of running unit tests on the project. Because the project doesn’t yet have any unit tests, that report will be uninteresting.

The libs folder should contain a JAR file that is named after the project’s folder. Further down, you’ll see how you can specify the name of the JAR and its version.



Build your project with Gradle Wrapper

gradle wrapper

./gradlew build


./gradlew run

# gradlewrapper
