1����mysql���ݿ⣬��Ҫ�������ã�
<!-- jdbc mysql  -->
		<jdbc.driver.groupId>mysql</jdbc.driver.groupId>
		<jdbc.driver.artifactId>mysql-connector-java</jdbc.driver.artifactId> 
		<jdbc.driver.version>5.1.11</jdbc.driver.version>

<property file="src/main/resources/application.properties" />
����������������ݿ�ĵ�ַ

������У�mvn antrun:run -Prefresh-db

2��mvn jetty:run