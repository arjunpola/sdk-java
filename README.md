
# Ticketmaster Java SDK for Android


## Android compatibility

This is a gradle Fork of the Ticketmaster Java SDK for use with Android. The project has been setup with
gradle using the same dependencies as the master branch. The maven files are kept for reference.

It builds successfully with [retrolambda](https://medium.com/android-news/retrolambda-on-android-191cc8151f85#.pbtrhv7g4 "retrolambda")
as a java library project for an android application.

I encountered runtime errors (related to the [Java 8 Optional container](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html "Java 8 Optional")
This could simply be a configuration issue or another backport or additional modifications to the master branch are needed.

## Building with java 7
sdk-java git: java -version

java version "1.7.0_79"
Java(TM) SE Runtime Environment (build 1.7.0_79-b15)
Java HotSpot(TM) 64-Bit Server VM (build 24.79-b02, mixed mode)

sdk-java git: ./gradlew build

BUILD SUCCESSFUL
Total time: 6.097 secs

