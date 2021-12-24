# maven-archetype-ae-simple

This is the simplest of archetypes for a maven project. No test folder or files, no packaging of the java files. Just a simple directory src/main/java and a POM.xml in the root, and that's it.

```sh
mvn -B archetype:generate -DarchetypeArtifactId=archetype-ae-simple -DarchetypeGroupId=com.aemaven -DarchetypeVersion=1.0-SNAPSHOT -DgroupId=com.aemaven -DartifactId=hello-world -Dversion=1.0
```

Also check out [Guide to Maven Archetype](https://www.baeldung.com/maven-archetype) for a good tutorial.