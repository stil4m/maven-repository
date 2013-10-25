# stil4m Maven Repository
---

## Available modules


| Name                         | Group Id  | Artifact ID                   | Latest version | Source |
|------------------------------|-----------|-------------------------------|----------------|--------|
|IMDb API                      | nl.stil4m | imdb-api                      | 1.0.1          | [Repository](https://github.com/stil4m/imdb-api) |
|Dropwizard Resource Reloading | nl.stil4m | dropwizard-resource-reloading | 1.0.0          | n/a |
|mo-mi: Mongo Migrations | nl.stil4m | mo-mi | 0.1.0          | [Repository](https://github.com/stil4m/mo-mi)  |
|Transmission RPC Java   | nl.stil4m | transmission-rpc-java  | 0.4.0          | [Repository](https://github.com/stil4m/transmission-rpc-java)  |
|iDeal API   | nl.stil4m | ideal-api  | 1.0.2          | [Repository](https://github.com/stil4m/ideal-api)  |
| Mandrill Client   | com.cribbstechnologies.clients | mandrillClient  | 0.0.3-SNAPSHOT          | [Repository](https://github.com/cribbstechnologies/Java-Mandrill-Wrapper)  |

## Repository management

### Maven

Add the following to your `pom.xml' to add this Maven repository:

```
<repository>
    <id>stil4m-releases</id>
    <name>stil4m-releases</name>
    <url>https://github.com/stil4m/maven-repository/raw/master/releases/</url>
</repository>
```

### Gradle

Add the following to the build.gradle in the correct section:

```
repositories {
    mavenCentral()
    maven {
        url 'https://github.com/stil4m/maven-repository/raw/master/releases/'
    }
}
```

For more info read [this](http://www.gradle.org/docs/current/userguide/artifact_dependencies_tutorial.html).
