# What is this?
This is the centralized [Scalafmt](https://github.com/scalameta/scalafmt/) configuration for Ubirch Scala-based systems.

## How to Use

### Maven
This [maven plugin](https://github.com/SimonJPegg/mvn_scalafmt) allows the use of the Scalafmt formatter in Maven.

Specify the [.scalafmt.conf](./.scalafmt.conf) when you set this plugin.

```
<configLocation>https://raw.githubusercontent.com/ubirch/ubirch-scalafmt-rules/main/.scalafmt.conf</configLocation>
```

### Sbt
Follow the [official documentation](https://scalameta.org/scalafmt/docs/installation.html#sbt).

### IntelliJ
You can apply this formatter when you run your project on IntelliJ.

Follow the [official documentation](https://scalameta.org/scalafmt/docs/installation.html#intellij).
