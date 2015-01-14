# Building the binary

Run the following command for building the binaries:

```
gradle buildAll
```

If you don't have gradle installed, you can use the gradlew script provided:

```
./gradlew buildAll
```

This should build the binaries without a gradle installation on your computer.

The gradle script will produce a zipped standalone version for all platforms. The zip files are located in the build/distributions folder.

# Building the binary with predefined visualisation

(1) Put your visualisation into the folder "resources/workspace".

(2) Run the following command, where XXX is the path to the html template file in the resources folder (e.g. myvis/vis.html):

```
gradle -Pvisualisation="myvis/vis.html" buildAll
```
