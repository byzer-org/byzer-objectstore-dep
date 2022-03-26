## byzer-objectstore-dep

### build azure-blob shade jar

```shell
# hadoop-2.7 compatible
mvn package -pl azure-blob -Pshade -Phadoop-2.7
# hadoop-3.2 compatible
mvn package -pl azure-blob -Pshade -Phadoop-3.2 
```

### build aws-s3 shade jar

```shell
# hadoop-2.7 compatible
mvn package -pl aws-s3 -Pshade -Phadoop-2.7
# hadoop-3.2 compatible
mvn package -pl aws-s3 -Pshade -Phadoop-3.2 
```

### build aliyun-oss shade jar

```shell
# hadoop-3.2 compatible
mvn package -pl aws-s3 -Pshade -Phadoop-3.2
```