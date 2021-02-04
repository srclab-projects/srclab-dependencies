# SrcLab BOM

用来对SrcLab中的项目及其第三方依赖进行版本管理，包括：

* srclab-bom: SrcLab中的项目的版本管理；
* srclab-dependencies: SrcLab中的项目的第三方依赖的版本管理。

## 使用方法

### 版本：

* bom-version: 1.1.1
* dependencies-version: 1.1.1

### srclab-bom

Gradle:

```groovy
api platform("xyz.srclab.bom:srclab-bom:{bom-version}")
```

Maven:

```xml

<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>xyz.srclab.bom</groupId>
            <artifactId>srclab-bom</artifactId>
            <version>{bom-version}</version>
            <type>pom</type>
            <scrop>import</scrop>
        </dependency>
    </dependencies>
</dependencyManagement>
```

### srclab-dependencies

Gradle:

```groovy
api platform("xyz.srclab.bom:srclab-dependencies:{dependencies-version}")
```

Maven:

```xml

<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>xyz.srclab.bom</groupId>
            <artifactId>srclab-dependencies</artifactId>
            <version>{dependencies-version}</version>
            <type>pom</type>
            <scrop>import</scrop>
        </dependency>
    </dependencies>
</dependencyManagement>
```

## 联系我们

* <srclab@163.com>
* QQ群: 1037555759
* [GitHub](https://github.com/srclab-projects/srclab-bom)

## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)