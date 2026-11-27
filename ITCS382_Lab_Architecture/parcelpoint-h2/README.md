# ParcelPoint, a layered command-line program

Build from this folder, then list the dependencies between its packages.

```
mvn package
jdeps -verbose:package -filter:none -e "parcelpoint.*" target/classes
```
