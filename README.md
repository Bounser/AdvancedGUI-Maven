# AdvancedGUI - Maven Repository

## Gradle

```kotlin
repositories {
    maven("https://bounser.github.io/AdvancedGUI-Maven/")
}

dependencies {
    compileOnly("me.leoko.advancedgui:AdvancedGUI:3.0.5")
}
```

## Maven

```xml
<repository>
  <id>advancedgui-releases</id>
  <name>AdvancedGUI</name>
  <url>https://bounser.github.io/AdvancedGUI-Maven/</url>
</repository>
```

```xml
<dependency>
  <groupId>me.leoko.advancedgui</groupId>
  <artifactId>AdvancedGUI</artifactId>
  <version>3.0.5</version>
  <scope>provided</scope>
</dependency>
```

The dependency must be `provided` / `compileOnly`

Declare it in your `plugin.yml`:

```yaml
depend: [AdvancedGUI]
```

See the [API documentation](https://bounser.github.io/AdvancedGUI-Maven/apidocs/) for usage.
