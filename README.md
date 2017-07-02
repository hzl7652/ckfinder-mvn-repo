maven repository
=================

###1 add repository to pom.xml

```xml
<repositories>
	 <repository>
		<id>ckfinder-mvn-repo-on-github</id>
		<url>https://raw.github.com/hzl7652/ckfinder-mvn-repo/master/</url>
	</repository>
</repositories>
```
###2 add dependency to pom.xml
```xml
<dependency>
	<groupId>org.beanio</groupId>
	<artifactId>beanio-ext</artifactId>
	<version>2.1.0</version>
</dependency>
```