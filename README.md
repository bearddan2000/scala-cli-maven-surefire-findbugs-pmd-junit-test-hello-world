# scala-cli-maven-surefire-findbugs-pmd-junit-test-hello-world

## Description
A POC for maven app using JUnit
framework with surefire plugin.
Analyze source code for potential bugs.
Analyze source code for bugs.

## Tech stack
- scala
- maven
	- findbugs
	- pmd
  - junit
  - surefire

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/maven-modules/maven-integration-test)
