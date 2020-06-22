# build 

## [jdk12](https://www.oracle.com/java/technologies/javase/jdk12-archive-downloads.html)

## idea setting

* jvm setting

```
-Des.path.conf=D:\github\java\elasticsearch-7.2.1\config
-Djava.security.policy=D:\github\java\elasticsearch-7.2.1\config\java.policy
-Des.path.home=D:\github\java\elasticsearch-7.2.1\data
-Dlog4j2.disable.jmx=true
```

* [x] include dependencies with `Provided` scope

## run

> org.elasticsearch.bootstrap.Elasticsearch