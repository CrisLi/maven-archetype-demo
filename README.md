# How to use

### Install the archetype to your local maven repository
```
$ mvn clean install
```

### Generate a new project
```
$ mvn archetype:generate -DarchetypeGroupId=org.chris.demo -DarchetypeArtifactId=maven-archetype-demo -DarchetypeVersion=1.0.0 -DgroupId=org.chris.demo -DartifactId=demo-service -Dversion=1.0.0-SNAPSHOT -DinteractiveMode=false -DarchetypeCatalog=internal -Dpackage=org.chris.demo
```

### Rename application name in the bootstrap.yaml file

Change the `spring.application.name` in the bootstrap*.yaml files under src/main/resources folders.
