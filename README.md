# About

extJWNL WordNet 2.1 Data contains dictionary files
from Unix version of WordNet 2.1 augmented with
a configuration file for extJWNL for extremely easy
use of WordNet-like semantic resources in your project.

# Getting started

In the pom.xml:

```xml
<dependency>
    <groupId>net.sf.extjwnl</groupId>
    <artifactId>extjwnl</artifactId>
    <version>1.7</version>
</dependency>
<dependency>
    <groupId>net.sf.extjwnl</groupId>
    <artifactId>extjwnl-data-wn21</artifactId>
    <version>1.0</version>
</dependency>
```

In the code:

```java
Dictionary d = Dictionary.getDefaultResourceInstance();
```
