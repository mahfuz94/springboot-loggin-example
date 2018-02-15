# springboot-logging-example

In this project, I have explained how to add logging facilities in project (slf4j)

You must see the application.properties file for configuration

1-> logging level can be
	* trace
	* debug
	* info
	* error
	* warn
	
for example logging.level.root=debug (for debug mode)
	
2-> To save logging details in file	
	logging.file=filename
	
3-> logging pattern
		* logging pattern for file
			%d{yyyy-MM-dd HH:mm:ss} [%thread] %-5level %logger{36} - %msg%n
		* loggin pattern for console
				%d{yyyy-MM-dd HH:mm:ss} - %msg%n
	
4-> Use of logback.xml file
	 If you don't like spring boot template, you can choose classic logback.xml file
	 more about classic logback file you can see mkyoung.com