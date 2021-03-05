# SrcLab BOM: SrcLab BOM (Bill of Materials) Project

## Variables

* author: Sun Qian
* bom-version: 1.1.1

## Revision

|Date|Revision|Author|Content|
|---|---|---|---|
|2020-11-11|1.0.0|{author}|New|
|2021-2-5|1.1.1|{author}|Big update|

## Introduction

SrcLab BOM is dependencies management for SrcLab projects, including:

* srclab-bom: SrcLab projects dependencies management;
* srclab-dependencies: third party dependencies management.

## Getting

### Gradle

```groovy
api platform("xyz.srclab.bom:srclab-bom:{bom-version}")
```

Or

```groovy
api platform("xyz.srclab.bom:srclab-dependencies:{bom-version}")
```

### Maven

```xml

<dependency>
  <groupId>xyz.srclab.bom</groupId>
  <artifactId>srclab-bom</artifactId>
  <version>{bom-version}</version>
  <type>pom</type>
  <scope>import</scope>
</dependency>
```

Or

```xml

<dependency>
  <groupId>xyz.srclab.bom</groupId>
  <artifactId>srclab-dependencies</artifactId>
  <version>{bom-version}</version>
  <type>pom</type>
  <scope>import</scope>
</dependency>
```

### Source Code

https://github.com/srclab-projects/srclab-bom

## Contribution and Contact

* fredsuvn@163.com
* https://github.com/srclab-projects/srclab-bom
* QQ group: 1037555759

## License

[Apache 2.0 license][license]

[license]: https://www.apache.org/licenses/LICENSE-2.0.html