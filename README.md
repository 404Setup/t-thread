# T2hread

[![Maven Central Version](https://img.shields.io/maven-central/v/one.tranic/t-thread)](https://central.sonatype.com/artifact/one.tranic/t-thread)
[![javadoc](https://javadoc.io/badge2/one.tranic/t-thread/javadoc.svg)](https://javadoc.io/doc/one.tranic/t-thread)

No need to install TLIB Base, need Java 17.

## Install
Please use shadow to remap T2hread to your own path to avoid conflicts with other libraries/plugins using TProxy.

`maven`

```xml
<dependency>
    <groupId>one.tranic</groupId>
    <artifactId>t-thread</artifactId>
    <version>[VERSION]</version>
</dependency>
```

`Gradle (Groovy)`
```groovy
repositories {
    mavenCentral()
}

dependencies {
    implementation 'one.tranic:t-thread:[VERSION]'
}
```

`Gradle (Kotlin DSL)`
```kotlin
repositories {
    mavenCentral()
}

dependencies {
    implementation("one.tranic:t-thread:[VERSION]")
}
```