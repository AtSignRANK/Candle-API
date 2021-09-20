# CANDLE API

[![Kotlin](https://img.shields.io/badge/kotlin-1.5.21-585DEF.svg?logo=kotlin)](http://kotlinlang.org)
[![Gradle](https://img.shields.io/badge/gradle-7.0-02303A.svg?logo=gradle)](https://gradle.org)

Maven
```xml
<dependency>
    <groupId>com.github.AtSignRANK</groupId>
    <artifactId>Candle-API</artifactId>
    <version>Version</version>
</dependency>
```

Gradle (Groovy DSL)
```gradle
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    implementation 'com.github.AtSignRANK:Candle-API:Version'
}
```

Gradle (Kotlin DSL)
```kts
repositories {
    maven('https://jitpack.io')
}

dependencies {
    implementation('com.github.AtSignRANK:Candle-API:Version')
}
```

Sample
```kotlin
fun sample(material: Material) {
    if (material.isCandle()) {
        material.type = Material.DIAMOND_SWORD
    }
}
```