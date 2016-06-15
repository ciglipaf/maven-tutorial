# Maven

## What is maven?

- Build tool
- Project management tool
	- dependency management
	- generate reports

## Common problems

- Multiple jars
	- need to bundle lots of jars to get them working
- Dependencies and versions
	- need to know which versions works well with each jar
- Project structure
- Building, publishing and deploying

## Creating Test

* `mvn archetype:generate`
* Predefined  structures are listed. Hit enter for this test tutorial.(it means we chose default)
* Versions of archetype are listed. Hit enter for this test tutorial. (it means we chose default)
* `groupId`type package name here.
* `artifactId`think this like a classname, it will be the name of the jar.
* `version`Hit enter for this test tutorial. (it means we chose default)
* `package`Hit enter for this test tutorial. (it means we chose default)
* type `y`and hit enter to confirm configurations.

## pom.xml

- `<packaging>` will be build as this, lets say *jar*
- `<name>` application name which will be saved as. This may be different from `<artifactId>`

### Kaynaklar
[Maven İndir](http://maven.apache.org/download.cgi)
[Environment Kurulumu](http://www.tutorialspoint.com/maven/maven_environment_setup.htm)
[Tutorial](https://www.youtube.com/watch?v=al7bRZzz4oU)
