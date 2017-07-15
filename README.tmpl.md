${HEADER}

#The Dollar Parent Maven Project ${STATE_BETA}

The artifacts used to build the Dollar project can be accessed using

```xml
    <repositories>
        <repository>
            <snapshots>
                <enabled>false</enabled>
            </snapshots>
            <id>bintray-sillelien-maven</id>
            <name>bintray</name>
            <url>http://dl.bintray.com/sillelien/maven</url>
        </repository>
    </repositories>
```  

and

```xml
        <dependency>
            <groupId>com.sillelien</groupId>
            <artifactId>dollar-parent</artifactId>
            <version>${RELEASE}</version>
        </dependency>
```


Dependencies: [![Dependency Status](https://www.versioneye.com/user/projects/54ae285534ff3e2204000002/badge.svg?style=flat)](https://www.versioneye.com/user/projects/54ae285534ff3e2204000002)

Please check out http://sillelien.github.io/dollar for latest details.
