# BMotion Studio for ProB Standalone

## Building BMotion Studio for ProB Standalone

Run the following command for building the standalone version of BMotion Studio for ProB, where xxx is the target platform:

```
gradle clean standalone_xxx
```

The following values are allowed for xxx: linux64, linux32, osx64, win32.

Or just run the following command for building the standalone version for all platforms:

```
gradle clean standalone_all
```

The build script will produce a zipped standalone version for all platforms. The zip files are located in the build/distribution folder.

## No Gradle installed?

If you don't have gradle installed, you can use the gradlew script provided. For instance, use

```
./gradlew clean standalone_linux64
```

to build the standalone version for linux64.

This should build the binaries without a gradle installation on your computer.
