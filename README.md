# Mavenized OpenOrd layout for gephi

This is a mavenized version of the Chinese Whispers Clustering Plugin for Gephi. You can use this plugin e.g. if you use the Gephi toolkit in your application and want to manage dependencies with maven.

## Installation

- Checkout the repository
- Run `mvn install`
- Add the dependency to your pom.xml:

```xml
<dependency>
    <groupId>de.uni_leipzig.informatik.asv.gephi.chinesewhispers</groupId>
    <artifactId>cw-cluster-plugin</artifactId>
    <version>0.7</version>
</dependency>
```

## Credits
The plugin itself was written by [efi](https://github.com/efi). The original source code can be found at [https://github.com/efi/gephi-cw](https://github.com/efi/gephi-cw). I added only the pom.xml for Maven and removed some UI files.