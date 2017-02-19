# multi-module-maven-project

Testing mult-module project with Maven

## Creating your first application with Maven

```
mvn archetype:generate
  -DgroupId=com.mycompany.app
  -DartifactId=my-app
  -DarchetypeArtifactId=maven-archetype-quickstart
  -DinteractiveMode=false
```
### Example
```
mvn archetype:generate -DgroupId=org.elementalsource.register -DartifactId=register-service -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```

## Commands to update your project
- `mvn versions:set -DgenerateBackupPoms=false -DnewVersion=your_new_version`
- `mvn -N versions:update-child-modules`
- `mvn versions:display-dependency-updates` Displays all dependencies that have newer versions available
- `mvn versions:use-latest-versions`
- `mvn versions:commit`
- `mvn dependency:tree`

## References
- http://www.mojohaus.org/versions-maven-plugin/use-latest-versions-mojo.html
- http://www.mojohaus.org/versions-maven-plugin/examples/update-child-modules.html
- https://dzone.com/articles/why-i-never-use-maven-release
