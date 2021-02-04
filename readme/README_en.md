# SrcLab BOM

BOM of SrcLab projects and third party dependencies, including:

* srclab-bom: BOM of SrcLab projects;
* srclab-dependencies: BOM of third party dependencies (SrcLab projects depend on this).

## Using

### Version:

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

## Contact

* <srclab@163.com>
* QQ group: 1037555759
* [GitHub](https://github.com/srclab-projects/srclab-bom)

## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)