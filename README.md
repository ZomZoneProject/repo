# MAVEN_REPOSITORY

```xml
<repositories>
    <repository>
        <id>github</id>
        <name>ZomZone Project Maven Packages</name>
        <url>https://maven.pkg.github.com/zomzoneproject/repo</url>
        <releases>
            <enabled>true</enabled>
        </releases>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
    </repository>
</repositories>
```

```xml
<dependencies>
    <dependency>
        <groupId>net.monkeyfunky.devteam</groupId>
        <artifactId>zomzonecore</artifactId>
        <version>1.0.4</version>
    </dependency>
    <dependency>
        <groupId>net.monkeyfunky.devteam</groupId>
        <artifactId>zomzonestatus</artifactId>
        <version>1.0</version>
    </dependency>
</dependencies>
```