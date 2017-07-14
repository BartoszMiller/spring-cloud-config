# spring-cloud-config
Simple example with Spring Cloud Config and Spring Boot

##### Server is secured with BASIC authenticaton provided by Spring Security:
username: *user*
password: *pa$$word*

##### URL to access script with resolved properties
Template: http://localhost:8888/{app-name}/{spring-profile}/{git-branch}/{file.name}

e.g. http://localhost:8888/citi-rds/PROD/master/script.sh
