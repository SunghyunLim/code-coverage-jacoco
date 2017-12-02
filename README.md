# code-coverage-jacoco
You can create code coverage reports by running the following commands on command line:

mvn clean test (Creates code coverage report for unit tests)

mvn clean verify -P integration-test (Creates code coverage report for integration tests)

mvn clean verify -P all-tests (Creates code coverage reports for unit and integration tests)

copied from https://github.com/pkainulainen/maven-examples/tree/master/code-coverage-jacoco
