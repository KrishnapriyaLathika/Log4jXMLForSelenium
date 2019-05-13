# Log4jXMLForSelenium
Log4j Config XML file For Selenium Java Framework

# For GRADLE. In Build.Gradle include the following Dependencies:
# For Log4j
testCompile (group: 'org.apache.logging.log4j', name: 'log4j-core', version: '2.11.1')
testCompile (group: 'org.apache.logging.log4j', name: 'log4j-api', version: '2.11.1')

# For Maven. In POM.XML use the following:
# For log4j dependency
<dependency>
  <groupId>org.apache.logging.log4j</groupId>
  <artifactId>log4j-core</artifactId>
  <version>2.11.1</version>
</dependency>
<dependency>
  <groupId>org.apache.logging.log4j</groupId>
  <artifactId>log4j-api</artifactId>
  <version>2.11.1</version>
</dependency>

# Where to Place?
  Create the log4j2-test.xml file in the Selenium Framework
  Path: src > test > resources
