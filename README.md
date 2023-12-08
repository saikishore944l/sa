<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/201/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/maven-v4_0_0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<groupId>in.RAHAM</groupId>
	<artifactId>NETFLIX</artifactId>
	<packaging>war</packaging>
	<version>1.2.2</version>
	<name>Java Home myweb</names>
	<url>http://maven.apache.org</url>
	
	<properties>
		<docker.image.prefix>kammana</docker.image.prefix>
	</properties>	
	<dependencies>
		<dependency>
		    <groupId>com.oracle.bedrock</groupId>
		    <artifactId>bedrock-runtime-maven</artifactId>
		    <version>5.1.2</version>
		</dependency>
		
		<dependency>
			<groupId>junit</groupId>
			<artifactId>junit</artifactId>
			<version>3.8.1</version>
			<scope>test</scope>
		</dependency>

	</dependencies>
	
	<distributionManagement>
		 <snapshotRepository>
		    <id>nexusRepo</id>
		    <url>http://13.233.230.166:8081/repository/maven-snapshots/</url>
		 </snapshotRepository>
		
		<repository>
		    <id>nexusRepo</id>
		    <url>http://13.233.230.166:8081/repository/maven-releases/</url>
		</repository>
  	</distributionManagement>
	
	<pluginRepositories>
	    <pluginRepository>    
		<id>maven1</id>
		<name>Maven.org</name>
		<url>http://repo1.maven.org/maven2</url>
	    </pluginRepository>
	</pluginRepositories>

	
</project>
