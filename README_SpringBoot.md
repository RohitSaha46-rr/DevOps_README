# Instructions to create a SpringBoot Application

Pre-requisite : Ecipse, Java 1.8 and Maven 3.x needs to installed and path variable must be configured.

1. Create a Maven Project in Eclipse > Skip Archetype Selection > Provide Archetype details manually.
```bash
<groupId>org.devops</groupId>
<artifactId>devops-test-app</artifactId>
<version>0.0.1-SNAPSHOT</version>
 ```

2. open the pom.xml and add the following lines.
    ```bash
    <parent>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-parent</artifactId>
        <version>2.0.3.RELEASE</version>
        <relativePath />
    </parent>
  
  
<dependencies>
	 <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-web</artifactId>
        </dependency>
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-test</artifactId>
            <scope>test</scope>
        </dependency>
</dependencies>
  
<properties>
	 <java.version>1.8</java.version>
</properties>
```