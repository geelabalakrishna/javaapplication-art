# javaapplication-art
javaapplication-art


```
automatic deploy into tomcat



 <plugins>
                        <plugin>
                                <groupId>org.apache.tomcat.maven</groupId>
                                <artifactId>tomcat7-maven-plugin</artifactId>
                                <version>2.2</version>
                                <configuration>
                                <path>/${project.artifactId}##${project.version}</path>
                                <url>http://localhost:8080/manager/text</url>
                                        <username>admin</username>
                                        <password>adminadmin</password>
                                        <update>true</update>
                                </configuration>
                        </plugin>
                </plugins>


mvn clean tomcat7:deploy

```
```
[ root@ip-10-10-2-223 ~/.m2/repository/com ]# tree
.
├── access
│   └── login
│       ├── 1.0
│       │   ├── login-1.0.pom
│       │   ├── login-1.0.war
│       │   └── _remote.repositories
│       └── maven-metadata-local.xml
```


```
