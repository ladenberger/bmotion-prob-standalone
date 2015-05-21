# Building BMotion Studio for ProB standalone

Run the following command for building the standalone version of BMotion Studio for ProB:

```
gradle clean standaloneDist
```

The build script will produce a zipped standalone version for all platforms. The zip files are located in the standalone/build/distribution folder.

# Building BMotion Studio for ProB online

Run the following command for building the online version of BMotion Studio for ProB:

```
gradle clean onlineDist
```
The build script will produce a zipped standalone version for all platforms. The zip files are located in the online/build/distribution folder.

# No Gradle installed?

If you don't have gradle installed, you can use the gradlew script provided. For instance, use

```
./gradlew clean standaloneDist
```

to build the standalone version or

```
./gradlew clean onlineDist
```

to build the online version.

This should build binaries without a gradle installation on your computer.
