jmef
====
 maven project based on fork of https://github.com/vincentfpgarcia/jMEF

Add this as a dependecy to your maven project via adding the following to your maven `settings.xml`:

```
 <dependencies>
        <dependency>
            <groupId>com</groupId>
            <artifactId>jmef</artifactId>
            <version>0.0.1</version>
        </dependency>
    </dependencies>
    <repositories>
        <repository>
            <!--<id>jmef-mvn-repo</id>-->
            <id>mvn-repo</id>
            <url>https://raw.github.com/mulloymorrow/jmef/mvn-repo/</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
    </repositories>
 ```
