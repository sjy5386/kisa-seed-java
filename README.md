# kisa-seed-java

[![Maven Central](https://img.shields.io/maven-central/v/com.sysbot32/kisa-seed-java)](https://search.maven.org/artifact/com.sysbot32/kisa-seed-java)
[![javadoc](https://javadoc.io/badge2/com.sysbot32/kisa-seed-java/javadoc.svg)](https://javadoc.io/doc/com.sysbot32/kisa-seed-java)

Unmodified [SEED](https://en.wikipedia.org/wiki/SEED) source codes
from [seed.kisa.or.kr](https://seed.kisa.or.kr).

## Usage

Maven

```xml

<dependency>
    <groupId>com.sysbot32</groupId>
    <artifactId>kisa-seed-java</artifactId>
    <version>1.0.1</version>
</dependency>
```

Gradle (Groovy)

```groovy
implementation 'com.sysbot32:kisa-seed-java:1.0.1'
```

Gradle (Kotlin)

```kotlin
implementation("com.sysbot32:kisa-seed-java:1.0.1")
```

## Development

The KISA sample programs (`main` classes) are located in `src/test/java`, so they are not included in the published
artifacts. Run them with:

```shell
mvn test-compile exec:java@ccm
mvn test-compile exec:java@cmac
mvn test-compile exec:java@gcm
```
