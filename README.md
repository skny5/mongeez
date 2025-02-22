### Note: This is a fork of https://github.com/mongeez/mongeez

It uses a different maven groupId.

Latest release:

```xml
<dependency>
    <groupId>com.github.adangel.org.mongeez</groupId>
    <artifactId>mongeez</artifactId>
    <version>0.9.7-adangel</version>
</dependency>
```
Maven repo for releases - https://repo.maven.apache.org/maven2/com/github/adangel/org/mongeez



To use the snapshot:

```xml
<dependency>
    <groupId>com.github.adangel.org.mongeez</groupId>
    <artifactId>mongeez</artifactId>
    <version>0.9.8-adangel-SNAPSHOT</version>
</dependency>
```

With the snapshot repository:

```xml
<repositories>
    <repository>
        <id>sonatype-nexus-snapshots</id>
        <name>Sonatype Nexus Snapshots</name>
        <url>https://oss.sonatype.org/content/repositories/snapshots</url>
        <releases>
            <enabled>false</enabled>
        </releases>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
    </repository>
</repositories>
```




### What is mongeez?

mongeez allows you to manage changes of your mongo documents and propagate these changes in sync with your code changes when you perform deployments.

For further information and usage guidelines check out [the wiki](https://github.com/mongeez/mongeez/wiki/How-to-use-mongeez).

###  Join the user group
http://groups.google.com/group/mongeez-users

### Become a contributor
http://groups.google.com/group/mongeez-dev


### Add mongeez to your project
```xml
<dependency>
    <groupId>org.mongeez</groupId>
	<artifactId>mongeez</artifactId>
	<version>0.9.6</version>
</dependency>
```

Maven repo for releases - http://repo1.maven.org/maven2

Internal versions - https://oss.sonatype.org/content/groups/public


### Or download mongeez from
repo1.maven.org - http://repo1.maven.org/maven2/org/mongeez/mongeez

### Travis Continuous Integration Build Status

Hopefully this thing is routinely green. Travis-CI monitors new code to this project and tests it on a variety of JDKs.

[![Build Status](https://travis-ci.org/skny5/mongeez.png?branch=adangel-fork)](https://travis-ci.org/skny5/mongeez)

## License
Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0
