# BDD in Scala - ScalaTest vs Cucumber vs Specs2

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f275cafaf4d1467780924c8de9eb74c6)](https://www.codacy.com/app/bmbferreira/BddScalaTestVsCucumberVsSpecs2?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=bmbferreira/BddScalaTestVsCucumberVsSpecs2&amp;utm_campaign=Badge_Grade)

Small SBT project with a simple Bank Account implementation 
making use of three different testing tools  (Cucumber, ScalaTest and Specs2)
in order to compare each one of them about how Behavioural Driven Development can be put in practice in Scala projects.

To run all the tests just run ``` sbt test ```.

## ScalaTest
 
To run only the tests that are using ScalaTest:

``` sbt 'testOnly bank.scalatest.*' ``` 

## Cucumber

To run only the tests that are using Cucumber:

``` sbt 'testOnly bank.cucumber.*' ``` 


## Specs2 

To run only the tests that are using Specs2:

``` sbt 'testOnly bank.specs2.*' ``` 


