MANJU IS SHOUTING
this is to test git 1


<?xml version="1.0" encoding="UTF-8"?>

-<project xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://maven.apache.org/POM/4.0.0">

<modelVersion>4.0.0</modelVersion>

<groupId>com.rolta.invmgmt</groupId>

<artifactId>InvDataMgr</artifactId>

<version>0.0.1-SNAPSHOT</version>

<packaging>war</packaging>

<name>InvDataMgr Maven Webapp</name>

<!-- FIXME change it to the project's website -->


<url>http://www.example.com</url>


-<properties>

<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>

<maven.compiler.source>1.8</maven.compiler.source>

<maven.compiler.target>1.8</maven.compiler.target>

<angular.project.location>module5x</angular.project.location>

<angular.project.nodeinstallation>node_installation</angular.project.nodeinstallation>

<sso-agent.version>1.2.0</sso-agent.version>

<commons-collection.version>3.1</commons-collection.version>

<commons-io.version>2.4</commons-io.version>

<commons-logging.version>1.2</commons-logging.version>

<jasypt-hibernate3.version>1.9.0</jasypt-hibernate3.version>

<wso2Agent.version>1.2</wso2Agent.version>

<opensaml.version>2.4.1</opensaml.version>

<xmltooling.version>1.3.2-1</xmltooling.version>

<xmlsec.version>1.3.0</xmlsec.version>

<junit.jupiter.version>5.0.0-M4</junit.jupiter.version>

<junit.platform.version>1.0.0-M4</junit.platform.version>

<json-simple.version>1.1</json-simple.version>

</properties>


-<dependencies>


-<dependency>

<groupId>com.googlecode.json-simple</groupId>

<artifactId>json-simple</artifactId>

<version>${json-simple.version}</version>

</dependency>


-<dependency>

<groupId>commons-lang</groupId>

<artifactId>commons-lang</artifactId>

<version>2.6</version>

</dependency>


-<dependency>

<groupId>org.junit.jupiter</groupId>

<artifactId>junit-jupiter-engine</artifactId>

<version>${junit.jupiter.version}</version>

</dependency>


-<dependency>

<groupId>org.junit.platform</groupId>

<artifactId>junit-platform-runner</artifactId>

<version>${junit.platform.version}</version>

<scope>test</scope>

</dependency>


-<dependency>

<groupId>commons-io</groupId>

<artifactId>commons-io</artifactId>

<version>${commons-io.version}</version>

</dependency>


-<dependency>

<groupId>commons-collections</groupId>

<artifactId>commons-collections</artifactId>

<version>${commons-collection.version}</version>

</dependency>


-<dependency>

<groupId>commons-logging</groupId>

<artifactId>commons-logging</artifactId>

<version>${commons-logging.version}</version>

</dependency>


-<dependency>

<groupId>apache-xmlsec</groupId>

<artifactId>xmlsec</artifactId>

<version>${xmlsec.version}</version>

</dependency>


-<dependency>

<groupId>com.rolta.oneview.platform</groupId>

<artifactId>sso-filter</artifactId>

<version>1.0</version>

</dependency>


-<dependency>

<groupId>org.ws02</groupId>

<artifactId>org.wso2.carbon.identity.sso.agent</artifactId>

<version>${sso-agent.version}</version>

</dependency>


-<dependency>

<groupId>org.opensaml</groupId>

<artifactId>opensaml</artifactId>

<version>${opensaml.version}</version>

</dependency>


-<dependency>

<groupId>org.ws02</groupId>

<artifactId>wso2Agent</artifactId>

<version>${wso2Agent.version}</version>

</dependency>


-<dependency>

<groupId>javax.enterprise</groupId>

<artifactId>cdi-api</artifactId>

<version>1.2</version>

</dependency>


-<dependency>

<groupId>org.hibernate.javax.persistence</groupId>

<artifactId>hibernate-jpa-2.1-api</artifactId>

<version>1.0.0.Final</version>

</dependency>


-<dependency>

<groupId>com.google.code.gson</groupId>

<artifactId>gson</artifactId>

<version>2.2.4</version>

</dependency>


-<dependency>

<groupId>commons-io</groupId>

<artifactId>commons-io</artifactId>

<version>2.0.1</version>

</dependency>


-<dependency>

<groupId>org.hibernate</groupId>

<artifactId>hibernate-entitymanager</artifactId>

<version>4.3.9.Final</version>

</dependency>


-<dependency>

<groupId>org.hibernate.common</groupId>

<artifactId>hibernate-commons-annotations</artifactId>

<version>4.0.5.Final</version>

</dependency>


-<dependency>

<groupId>org.hibernate.javax.persistence</groupId>

<artifactId>hibernate-jpa-2.1-api</artifactId>

<version>1.0.0.Final</version>

</dependency>


-<dependency>

<groupId>javax.ws.rs</groupId>

<artifactId>javax.ws.rs-api</artifactId>

<version>2.0.1</version>

</dependency>


-<dependency>

<groupId>org.opensaml</groupId>

<artifactId>xmltooling</artifactId>

<version>${xmltooling.version}</version>

</dependency>


-<dependency>

<groupId>com.sun.xml.ws</groupId>

<artifactId>jaxws-rt</artifactId>

<version>2.2.10</version>

</dependency>


-<dependency>

<artifactId>hibernate-ehcache</artifactId>

<groupId>org.hibernate</groupId>

<version>4.0.0.CR6</version>

</dependency>


-<dependency>

<groupId>org.jboss.spec</groupId>

<artifactId>jboss-javaee-all-7.0</artifactId>

<version>1.0.3.Final</version>

<scope>provided</scope>

</dependency>


-<dependency>

<groupId>dom4j</groupId>

<artifactId>dom4j</artifactId>

<version>1.6.1</version>

<scope>provided</scope>

</dependency>


-<dependency>

<groupId>org.jasypt</groupId>

<artifactId>jasypt</artifactId>

<version>1.9.2</version>

</dependency>


-<dependency>

<groupId>log4j</groupId>

<artifactId>log4j</artifactId>

<version>1.2.15</version>


-<exclusions>


-<exclusion>

<groupId>com.sun.jmx</groupId>

<artifactId>jmxri</artifactId>

</exclusion>


-<exclusion>

<groupId>com.sun.jdmk</groupId>

<artifactId>jmxtools</artifactId>

</exclusion>


-<exclusion>

<groupId>javax.jms</groupId>

<artifactId>jms</artifactId>

</exclusion>

</exclusions>

</dependency>


-<dependency>

<groupId>org.jasypt</groupId>

<artifactId>jasypt-hibernate3</artifactId>

<version>${jasypt-hibernate3.version}</version>


-<exclusions>


-<exclusion>

<groupId>org.hibernate</groupId>

<artifactId>hibernate</artifactId>

</exclusion>

</exclusions>

</dependency>


-<dependency>

<groupId>org.jboss.resteasy</groupId>

<artifactId>resteasy-jaxrs</artifactId>

<version>3.0.16.Final</version>

<scope>provided</scope>

</dependency>


-<dependency>

<groupId>org.jboss.resteasy</groupId>

<artifactId>resteasy-jackson-provider</artifactId>

<version>3.0.16.Final</version>

<scope>provided</scope>

</dependency>


-<dependency>

<groupId>com.fasterxml.jackson.core</groupId>

<artifactId>jackson-databind</artifactId>

<version>2.9.2</version>

</dependency>


-<dependency>

<groupId>org.jboss.resteasy</groupId>

<artifactId>resteasy-multipart-provider</artifactId>

<version>3.0.16.Final</version>

<scope>provided</scope>

</dependency>


-<dependency>

<groupId>junit</groupId>

<artifactId>junit</artifactId>

<version>4.11</version>

<scope>test</scope>

</dependency>

</dependencies>


-<build>

<finalName>InvDataMgr</finalName>


-<plugins>


-<plugin>

<groupId>com.github.eirslett</groupId>

<artifactId>frontend-maven-plugin</artifactId>

<version>1.0</version>


-<configuration>

<workingDirectory>${angular.project.location}</workingDirectory>

<installDirectory>${angular.project.nodeinstallation}</installDirectory>

</configuration>


-<executions>


-<execution>

<id>install node and npm</id>


-<goals>

<goal>install-node-and-npm</goal>

</goals>


-<configuration>

<nodeVersion>v8.11.1</nodeVersion>

<npmVersion>5.6.0</npmVersion>

</configuration>

</execution>

<!-- It will execute command "npm install" inside "/e2e-angular2" directory -->



-<execution>

<id>npm install</id>


-<goals>

<goal>npm</goal>

</goals>


-<configuration>

<arguments>install</arguments>

</configuration>

</execution>

<!-- It will execute command "npm build" inside "/e2e-angular2" directory to clean and create "/dist" directory -->



-<execution>

<id>npm build</id>


-<goals>

<goal>npm</goal>

</goals>


-<configuration>

<arguments>run build</arguments>

</configuration>

</execution>

</executions>

</plugin>


-<plugin>

<groupId>org.apache.maven.plugins</groupId>

<artifactId>maven-resources-plugin</artifactId>

<version>2.4.2</version>


-<executions>


-<execution>

<id>default-copy-resources</id>

<phase>process-resources</phase>


-<goals>

<goal>copy-resources</goal>

</goals>


-<configuration>

<overwrite>true</overwrite>

<outputDirectory>${project.build.directory}/${project.artifactId}</outputDirectory>


-<resources>


-<resource>

<directory>${project.basedir}/${angular.project.location}/dist</directory>

</resource>

</resources>

</configuration>

</execution>

</executions>

</plugin>

</plugins>

</build>

</project>
