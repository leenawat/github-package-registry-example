## deploy lib
```
mvn deploy -pl lib
```

## run sample
```
mvn compile exec:java -Dexec.mainClass="com.github.leenawat.sample.App" -pl sample
```

## reference
- [igabaydulin/github-package-registry-example](https://github.com/igabaydulin/github-package-registry-example)
- [Working with the Apache Maven registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-apache-maven-registry)
- [Run a Java Main Method in Maven](https://www.baeldung.com/maven-java-main-method)