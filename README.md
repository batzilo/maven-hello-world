# maven-hello-world

A simple hello world program in Java using Maven.

Build with:
```
$ mvn compile
```

Package with:
```
$ mvn package
```

Without `exec-maven-plugin`, run with:
```
$ java -cp target/hello-0.1.0.jar Hello
```

With `exec-maven-plugin`, run with:
```
$ mvn exec:java
```
