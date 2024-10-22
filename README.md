# ![logo](logo.svg) SrcLab Dependencies: Dependencies Management for [SrcLab]

<span id="author" class="author">Sun Qian</span>
<span id="email" class="email"><fredsuvn@163.com></span>

`srclab-dependencies` is a dependency management for [SrcLab] projects, provides version management for common third
party libs, as the role of `dependencyManagement` in Maven.

## Getting

Gradle:

```groovy
api platform("xyz.srclab.dependencies:srclab-dependencies:0.0.1")
```

Maven:

```xml

<dependencies>
  <dependency>
    <groupId>xyz.srclab.dependencies</groupId>
    <artifactId>srclab-dependencies</artifactId>
    <version>0.0.1</version>
    <type>pom</type>
    <scope>import</scope>
  </dependency>
</dependencies>
```

## Join

* QQ group: 566185308
* fredsuvn@163.com
* https://github.com/srclab-projects/srclab-dependencies

## License

[Apache 2.0 license][license]

[SrcLab]: https://github.com/srclab-projects

[license]: https://www.apache.org/licenses/LICENSE-2.0.html