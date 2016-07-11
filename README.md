# BMotionWeb for ProB Standalone Server

## Build

Run the following command for building the standalone server version of BMotionWeb:

```
gradle standalone
```

The build script will produce a zipped standalone version. The zip file is located in the build/distribution folder.

## No Gradle installed?

If you don't have gradle installed, you can use the gradlew script provided. For instance, use

```
./gradlew standalone
```

to build the standalone server version.

This should build the application without a gradle installation on your computer.
