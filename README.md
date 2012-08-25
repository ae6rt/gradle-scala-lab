
Demonstrate how to run a Scala app from a Gradle-managed project.

My Gradle version:

     $ gradle -version

     ------------------------------------------------------------
     Gradle 1.1
     ------------------------------------------------------------

     Gradle build time: Tuesday, July 31, 2012 1:24:32 PM UTC
     Groovy: 1.8.6
     Ant: Apache Ant(TM) version 1.8.4 compiled on May 22 2012
     Ivy: 2.2.0
     JVM: 1.6.0_33 (Apple Inc. 20.8-b03-424)
     OS: Mac OS X 10.6.8 x86_64

Run it:

    $ gradle runme -DSOME_PARAM=foo
    :compileJava UP-TO-DATE
    :compileScala
    :processResources UP-TO-DATE
    :classes
    :runme
    param: foo

    BUILD SUCCESSFUL
