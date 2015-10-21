# BMotion Studio for ProB Standalone

## Build

Run the following command for building the standalone version of BMotion Studio for ProB, where xxx is the target platform:

```
gradle clean standalone_xxx
```

The following values are allowed for xxx: linux64, linux32, leopard64, win32.

The build script will produce a zipped standalone version for the given platform. The zip file is located in the build/distribution folder.

## No Gradle installed?

If you don't have gradle installed, you can use the gradlew script provided. For instance, use

```
./gradlew clean standalone_linux64
```

to build the standalone version for linux x64.

This should build the application without a gradle installation on your computer.
