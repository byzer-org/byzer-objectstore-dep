## kolo-objectstore-dep

### build shade jar

```shell
# hadoop-2.7 compatible
mvn package -pl azure-blob -Pshade -Phadoop-2.7
# hadoop-3.2 compatible
mvn package -pl azure-blob -Pshade -Phadoop-3.2 
```