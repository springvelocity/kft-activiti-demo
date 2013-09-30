1，用mysql数据库，需要更改配置：
<!-- jdbc mysql  -->
		<jdbc.driver.groupId>mysql</jdbc.driver.groupId>
		<jdbc.driver.artifactId>mysql-connector-java</jdbc.driver.artifactId> 
		<jdbc.driver.version>5.1.11</jdbc.driver.version>

<property file="src/main/resources/application.properties" />
这个里面配置下数据库的地址

最后，运行：mvn antrun:run -Prefresh-db

2，mvn jetty:run