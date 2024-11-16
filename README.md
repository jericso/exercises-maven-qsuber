# Essentials
This is an exercise to create an executable Uber-JAR Maven template.

## Commands
mvn archetype:generate "-DarchetypeGroupId=org.apache.maven.archetypes" "-DarchetypeArtifactId=maven-archetype-quickstart" "-DarchetypeVersion=1.5" "-DgroupId=com.prolegoma.exercises.maven" "-DartifactId=qsuber"

mvn package

## Updates to POM

Added configuration for mainClass to create manifest to make JAR executable.

Updated Compiler Release for JDK 11.

## Git Ignore

Combined Java and Maven .gitignore files from GitHub.

## References

https://maven.apache.org/plugins/maven-assembly-plugin/usage.html

https://github.com/github/gitignore
