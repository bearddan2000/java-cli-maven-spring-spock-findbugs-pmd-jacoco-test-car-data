# java-cli-maven-spring-spock-findbugs-pmd-jacoco-test-car-data

## Description
Analyze source code for potential bugs.
A POC for spring app using spock framework
and jacoco and pmd plugins.

## Tech stack
- java
- groovy
- maven
	- findbugs
  - spring
  - spock
  - jacoco
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- pmd report found at bin/target/site
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://www.petrikainulainen.net/programming/testing/writing-unit-tests-with-spock-framework-creating-a-maven-project/)
- [Code build model](https://github.com/christoph-frick/spock-test-logging)
- [Jacoco config](https://www.baeldung.com/jacoco)
