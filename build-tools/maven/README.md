```
cd /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application; JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64 M2_HOME=/home/phuongtrinh/netbeans-8.2/apache-maven-3.5.0 /home/phuongtrinh/netbeans-8.2/apache-maven-3.5.0/bin/mvn clean install
Scanning for projects...

------------------------------------------------------------------------
Building wrappy-web-application 0.0.1-SNAPSHOT
------------------------------------------------------------------------

--- maven-clean-plugin:2.5:clean (default-clean) @ wrappy-web-application ---

--- maven-resources-plugin:2.6:resources (default-resources) @ wrappy-web-application ---
Using 'UTF-8' encoding to copy filtered resources.
skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/main/resources

--- maven-compiler-plugin:3.3:compile (default-compile) @ wrappy-web-application ---
Changes detected - recompiling the module!
Compiling 13 source files to /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/classes

--- maven-resources-plugin:2.6:testResources (default-testResources) @ wrappy-web-application ---
Using 'UTF-8' encoding to copy filtered resources.
skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/test/resources

--- maven-compiler-plugin:3.3:testCompile (default-testCompile) @ wrappy-web-application ---
Nothing to compile - all classes are up to date

--- maven-surefire-plugin:2.12.4:test (default-test) @ wrappy-web-application ---
No tests to run.

--- maven-war-plugin:2.2:war (default-war) @ wrappy-web-application ---
Packaging webapp
Assembling webapp [wrappy-web-application] in [/home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/8EF640C4836D96CE990B71F60E0EA1DB]
Processing war project
Copying webapp resources [/home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/main/webapp]
Webapp assembled in [151 msecs]
Building war: /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/8EF640C4836D96CE990B71F60E0EA1DB.war
WEB-INF/web.xml already added, skipping

--- maven-install-plugin:2.4:install (default-install) @ wrappy-web-application ---
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/8EF640C4836D96CE990B71F60E0EA1DB.war to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-web-application/0.0.1-SNAPSHOT/wrappy-web-application-0.0.1-SNAPSHOT.war
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/pom.xml to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-web-application/0.0.1-SNAPSHOT/wrappy-web-application-0.0.1-SNAPSHOT.pom
------------------------------------------------------------------------
BUILD SUCCESS
------------------------------------------------------------------------
Total time: 5.007 s
Finished at: 2018-01-22T09:12:58+07:00
Final Memory: 33M/366M
------------------------------------------------------------------------
```






```
% mvn clean install
WARNING: An illegal reflective access operation has occurred
WARNING: Illegal reflective access by com.google.inject.internal.cglib.core.$ReflectUtils$1 (file:/usr/share/maven/lib/guice.jar) to method java.lang.ClassLoader.defineClass(java.lang.String,byte[],int,int,java.security.ProtectionDomain)
WARNING: Please consider reporting this to the maintainers of com.google.inject.internal.cglib.core.$ReflectUtils$1
WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
WARNING: All illegal access operations will be denied in a future release
[INFO] Scanning for projects...
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] Building wrappy-web-application 0.0.1-SNAPSHOT
[INFO] ------------------------------------------------------------------------
Downloading: https://repo.maven.apache.org/maven2/com/twilio/sdk/twilio/maven-metadata.xml
Downloaded: https://repo.maven.apache.org/maven2/com/twilio/sdk/twilio/maven-metadata.xml (3.0 kB at 2.3 kB/s)
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ wrappy-web-application ---
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ wrappy-web-application ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/main/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.3:compile (default-compile) @ wrappy-web-application ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 13 source files to /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/classes
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ wrappy-web-application ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.3:testCompile (default-testCompile) @ wrappy-web-application ---
[INFO] Nothing to compile - all classes are up to date
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ wrappy-web-application ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-war-plugin:2.2:war (default-war) @ wrappy-web-application ---
[INFO] Packaging webapp
[INFO] Assembling webapp [wrappy-web-application] in [/home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/8EF640C4836D96CE990B71F60E0EA1DB]
[INFO] Processing war project
[INFO] Copying webapp resources [/home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/main/webapp]
[INFO] Webapp assembled in [681 msecs]
[INFO] Building war: /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/8EF640C4836D96CE990B71F60E0EA1DB.war
[INFO] WEB-INF/web.xml already added, skipping
[INFO] 
[INFO] --- maven-install-plugin:2.4:install (default-install) @ wrappy-web-application ---
[INFO] Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/8EF640C4836D96CE990B71F60E0EA1DB.war to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-web-application/0.0.1-SNAPSHOT/wrappy-web-application-0.0.1-SNAPSHOT.war
[INFO] Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/pom.xml to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-web-application/0.0.1-SNAPSHOT/wrappy-web-application-0.0.1-SNAPSHOT.pom
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 9.823 s
[INFO] Finished at: 2018-01-22T09:12:10+07:00
[INFO] Final Memory: 27M/91M
[INFO] ------------------------------------------------------------------------
```








```
cd /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring; JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64 M2_HOME=/home/phuongtrinh/netbeans-8.2/apache-maven-3.5.0 /home/phuongtrinh/netbeans-8.2/apache-maven-3.5.0/bin/mvn clean install
Scanning for projects...

Some problems were encountered while building the effective model for net.wrappy:wrappy-common:jar:0.0.1-SNAPSHOT
'dependencies.dependency.(groupId:artifactId:type:classifier)' must be unique: com.fasterxml.jackson.core:jackson-databind:jar -> duplicate declaration of version 2.7.2 @ line 135, column 15

It is highly recommended to fix these problems because they threaten the stability of your build.

For this reason, future Maven versions might no longer support building such malformed projects.

------------------------------------------------------------------------
Reactor Build Order:

net.wrappy 1.0
wrappy-entity
wrappy-common
wrappy-extern
wrappy-application
wrappy-web-application

------------------------------------------------------------------------
Building net.wrappy 1.0 0.0.1-SNAPSHOT
------------------------------------------------------------------------

--- maven-clean-plugin:2.5:clean (default-clean) @ wrappy-parent ---

--- maven-install-plugin:2.4:install (default-install) @ wrappy-parent ---
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/pom.xml to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-parent/0.0.1-SNAPSHOT/wrappy-parent-0.0.1-SNAPSHOT.pom

------------------------------------------------------------------------
Building wrappy-entity 0.0.1-SNAPSHOT
------------------------------------------------------------------------

--- maven-clean-plugin:2.5:clean (default-clean) @ wrappy-entity ---

--- maven-processor-plugin:3.1.0:process (process) @ wrappy-entity ---
diagnostic: Note: Hibernate JPA 2 Static-Metamodel Generator 5.1.0.Final

--- maven-resources-plugin:2.6:resources (default-resources) @ wrappy-entity ---
Using 'UTF-8' encoding to copy filtered resources.
Copying 3 resources

--- maven-compiler-plugin:3.3:compile (default-compile) @ wrappy-entity ---
Changes detected - recompiling the module!
Compiling 73 source files to /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-entity/target/classes

--- maven-resources-plugin:2.6:testResources (default-testResources) @ wrappy-entity ---
Using 'UTF-8' encoding to copy filtered resources.
skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-entity/src/test/resources

--- maven-compiler-plugin:3.3:testCompile (default-testCompile) @ wrappy-entity ---
No sources to compile

--- maven-surefire-plugin:2.12.4:test (default-test) @ wrappy-entity ---
No tests to run.

--- maven-jar-plugin:2.4:jar (default-jar) @ wrappy-entity ---
Building jar: /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-entity/target/wrappy-entity-0.0.1-SNAPSHOT.jar

--- maven-install-plugin:2.4:install (default-install) @ wrappy-entity ---
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-entity/target/wrappy-entity-0.0.1-SNAPSHOT.jar to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-entity/0.0.1-SNAPSHOT/wrappy-entity-0.0.1-SNAPSHOT.jar
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-entity/pom.xml to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-entity/0.0.1-SNAPSHOT/wrappy-entity-0.0.1-SNAPSHOT.pom

------------------------------------------------------------------------
Building wrappy-common 0.0.1-SNAPSHOT
------------------------------------------------------------------------

--- maven-clean-plugin:2.5:clean (default-clean) @ wrappy-common ---

--- maven-resources-plugin:2.6:resources (default-resources) @ wrappy-common ---
Using 'UTF-8' encoding to copy filtered resources.
Copying 5 resources

--- maven-compiler-plugin:3.3:compile (default-compile) @ wrappy-common ---
Changes detected - recompiling the module!
Compiling 34 source files to /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-common/target/classes
/home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-common/src/main/java/net/wrappy/common/util/ZHConverter.java: Some input files use unchecked or unsafe operations.
/home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-common/src/main/java/net/wrappy/common/util/ZHConverter.java: Recompile with -Xlint:unchecked for details.

--- maven-resources-plugin:2.6:testResources (default-testResources) @ wrappy-common ---
Using 'UTF-8' encoding to copy filtered resources.
skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-common/src/test/resources

--- maven-compiler-plugin:3.3:testCompile (default-testCompile) @ wrappy-common ---
No sources to compile

--- maven-surefire-plugin:2.12.4:test (default-test) @ wrappy-common ---
No tests to run.

--- maven-jar-plugin:2.4:jar (default-jar) @ wrappy-common ---
Building jar: /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-common/target/wrappy-common-0.0.1-SNAPSHOT.jar

--- maven-install-plugin:2.4:install (default-install) @ wrappy-common ---
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-common/target/wrappy-common-0.0.1-SNAPSHOT.jar to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-common/0.0.1-SNAPSHOT/wrappy-common-0.0.1-SNAPSHOT.jar
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-common/pom.xml to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-common/0.0.1-SNAPSHOT/wrappy-common-0.0.1-SNAPSHOT.pom

------------------------------------------------------------------------
Building wrappy-extern 0.0.1-SNAPSHOT
------------------------------------------------------------------------

--- maven-clean-plugin:2.5:clean (default-clean) @ wrappy-extern ---

--- maven-resources-plugin:2.6:resources (default-resources) @ wrappy-extern ---
Using 'UTF-8' encoding to copy filtered resources.
skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-extern/src/main/resources

--- maven-compiler-plugin:3.3:compile (default-compile) @ wrappy-extern ---
Changes detected - recompiling the module!
Compiling 21 source files to /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-extern/target/classes

--- maven-resources-plugin:2.6:testResources (default-testResources) @ wrappy-extern ---
Using 'UTF-8' encoding to copy filtered resources.
skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-extern/src/test/resources

--- maven-compiler-plugin:3.3:testCompile (default-testCompile) @ wrappy-extern ---
No sources to compile

--- maven-surefire-plugin:2.12.4:test (default-test) @ wrappy-extern ---
No tests to run.

--- maven-jar-plugin:2.4:jar (default-jar) @ wrappy-extern ---
Building jar: /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-extern/target/wrappy-extern-0.0.1-SNAPSHOT.jar

--- maven-install-plugin:2.4:install (default-install) @ wrappy-extern ---
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-extern/target/wrappy-extern-0.0.1-SNAPSHOT.jar to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-extern/0.0.1-SNAPSHOT/wrappy-extern-0.0.1-SNAPSHOT.jar
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-extern/pom.xml to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-extern/0.0.1-SNAPSHOT/wrappy-extern-0.0.1-SNAPSHOT.pom

------------------------------------------------------------------------
Building wrappy-application 0.0.1-SNAPSHOT
------------------------------------------------------------------------

--- maven-clean-plugin:2.5:clean (default-clean) @ wrappy-application ---

--- maven-resources-plugin:2.6:resources (default-resources) @ wrappy-application ---
Using 'UTF-8' encoding to copy filtered resources.
Copying 4 resources

--- maven-compiler-plugin:3.3:compile (default-compile) @ wrappy-application ---
Changes detected - recompiling the module!
Compiling 169 source files to /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-application/target/classes

--- maven-resources-plugin:2.6:testResources (default-testResources) @ wrappy-application ---
Using 'UTF-8' encoding to copy filtered resources.
skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-application/src/test/resources

--- maven-compiler-plugin:3.3:testCompile (default-testCompile) @ wrappy-application ---
No sources to compile

--- maven-surefire-plugin:2.12.4:test (default-test) @ wrappy-application ---
No tests to run.

--- maven-jar-plugin:2.4:jar (default-jar) @ wrappy-application ---
Building jar: /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-application/target/wrappy-application-0.0.1-SNAPSHOT.jar

--- maven-install-plugin:2.4:install (default-install) @ wrappy-application ---
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-application/target/wrappy-application-0.0.1-SNAPSHOT.jar to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-application/0.0.1-SNAPSHOT/wrappy-application-0.0.1-SNAPSHOT.jar
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-application/pom.xml to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-application/0.0.1-SNAPSHOT/wrappy-application-0.0.1-SNAPSHOT.pom

------------------------------------------------------------------------
Building wrappy-web-application 0.0.1-SNAPSHOT
------------------------------------------------------------------------

--- maven-clean-plugin:2.5:clean (default-clean) @ wrappy-web-application ---

--- maven-resources-plugin:2.6:resources (default-resources) @ wrappy-web-application ---
Using 'UTF-8' encoding to copy filtered resources.
skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/main/resources

--- maven-compiler-plugin:3.3:compile (default-compile) @ wrappy-web-application ---
Changes detected - recompiling the module!
Compiling 13 source files to /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/classes
/home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/main/java/net/wrappy/controller/WpMemberEndpoint.java: /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/main/java/net/wrappy/controller/WpMemberEndpoint.java uses unchecked or unsafe operations.
/home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/main/java/net/wrappy/controller/WpMemberEndpoint.java: Recompile with -Xlint:unchecked for details.

--- maven-resources-plugin:2.6:testResources (default-testResources) @ wrappy-web-application ---
Using 'UTF-8' encoding to copy filtered resources.
skip non existing resourceDirectory /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/test/resources

--- maven-compiler-plugin:3.3:testCompile (default-testCompile) @ wrappy-web-application ---
No sources to compile

--- maven-surefire-plugin:2.12.4:test (default-test) @ wrappy-web-application ---
No tests to run.

--- maven-war-plugin:2.2:war (default-war) @ wrappy-web-application ---
Packaging webapp
Assembling webapp [wrappy-web-application] in [/home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/8EF640C4836D96CE990B71F60E0EA1DB]
Processing war project
Copying webapp resources [/home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/src/main/webapp]
Webapp assembled in [279 msecs]
Building war: /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/8EF640C4836D96CE990B71F60E0EA1DB.war
WEB-INF/web.xml already added, skipping

--- maven-install-plugin:2.4:install (default-install) @ wrappy-web-application ---
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/target/8EF640C4836D96CE990B71F60E0EA1DB.war to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-web-application/0.0.1-SNAPSHOT/wrappy-web-application-0.0.1-SNAPSHOT.war
Installing /home/phuongtrinh/Projects/netbeans/2017-net.wrappy.platform-be-spring/wrappy-web-application/pom.xml to /home/phuongtrinh/.m2/repository/net/wrappy/wrappy-web-application/0.0.1-SNAPSHOT/wrappy-web-application-0.0.1-SNAPSHOT.pom
------------------------------------------------------------------------
Reactor Summary:

net.wrappy 1.0 ..................................... SUCCESS [  0.604 s]
wrappy-entity ...................................... SUCCESS [  4.289 s]
wrappy-common ...................................... SUCCESS [  1.632 s]
wrappy-extern ...................................... SUCCESS [  0.413 s]
wrappy-application ................................. SUCCESS [  0.725 s]
wrappy-web-application ............................. SUCCESS [  3.780 s]
------------------------------------------------------------------------
BUILD SUCCESS
------------------------------------------------------------------------
Total time: 11.609 s
Finished at: 2018-01-22T10:28:48+07:00
Final Memory: 40M/575M
------------------------------------------------------------------------
```