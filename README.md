# spring-cloud-config
Simple example with Spring Cloud Config and Spring Boot backed by properties in https://github.com/BartoszMiller/spring-cloud-config-repo

##### Server is secured with BASIC authenticaton provided by Spring Security:
username: *user*
password: *pa$$word*

##### URL to access script with resolved properties
Template: http://localhost:8888/{app-name}/{spring-profile}/{git-branch}/{file.name}

e.g. 
1. http://localhost:8888/citi-rds/PROD/master/script.sh
2. http://localhost:8888/citi-rds/PROD/new-component/script.sh
