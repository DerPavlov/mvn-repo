Pavlovs maven repository
========

To add this repository to your maven project, add this to your pom.xml

    <repositories>
        <repository>
            <id>cannons-repo</id>
            <url>https://github.com/DerPavlov/mvn-repo/raw/master/</url>
            <!-- use snapshot version -->
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
        ...
    </repositories>
    
    <dependencies>
        <dependency>
            <groupId>at.pavlov</groupId>
            <artifactId>Cannons</artifactId>
            <version>2.2.1</version>
        </dependency>
        ...
    </dependencies>


