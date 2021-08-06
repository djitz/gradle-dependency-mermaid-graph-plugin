# gradle-dependency-mermaid-graph-plugin

Plugin to generate Gradle dependencies graph in Mermaid file format.

## Usage

1. Add plugin to target project's build.file:
    ```
    plugins {
       id "org.djitz.gradle-dependency-mermaid-graph-plugin" version "0.1-SNAPSHOT"
    }
   ```
2. Run task:
   ```
   $ ./gradlew drawDependenciesGraph
   ```