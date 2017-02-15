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
### Examples
```
mvn archetype:generate -DgroupId=org.elementalsource.register -DartifactId=register-service -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false &
mvn archetype:generate -DgroupId=org.elementalsource.infra    -DartifactId=infra-service    -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false &
mvn archetype:generate -DgroupId=org.elementalsource.business -DartifactId=business-service -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false &
mvn archetype:generate -DgroupId=org.elementalsourcefrontend  -DartifactId=frontend-service -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false &
```
