# More Spring Information ("One-To-Many" Relationship & Baeldung)

## [Related data in Spring (section 3."One-to-Many Relationship”)](https://www.baeldung.com/spring-data-rest-relationships)

Name a few real life examples of “One To Many” relatioships.

One to many is the contrast between singular and plural values. Some examples are a book -> a library, a flower -> a bouquet of flowers, an elephant -> a heard.

Given two entities, one named Player and one named Team, if you wanted to create a one to many relationship with those entities which would be the one and which would be the many?

One would be the Player, many would be Team.

Explain one to many relationships to a non-technical friend.

It is expanding a singular value in order to form a group or collection.

## [Baeldung: Spring Integration Testing](https://www.baeldung.com/integration-testing-in-spring)

Describe the difference between a unit test and an integration test.

From ChatGPT using prompt: In Baeldung, describe the difference between a unit test and an integration test.

> Unit Test:
>A unit test is a type of software testing where individual units or components of a software application are isolated and tested in isolation from the rest of the system. The purpose of unit testing is to verify that each unit of the software functions correctly and meets its specified requirements. A "unit" typically refers to the smallest testable part of an application, such as a function, method, or class.

>Integration Test:
>Integration testing is a level of software testing where multiple individual units or components are combined and tested together as a group. The main objective of integration testing is to expose any issues that may arise from interactions between these integrated units. The focus is on verifying that different parts of the application can work together harmoniously and produce the expected results.

This was very helpful in my understanding. The unit test is very specific and tageted, the integrtion test combines multiple units and test their interaction as a whole.

What is the object that provides support for Sprin MVC Testing?

The *WebApplicationContext* Object.

What does the “perform()” method do in a Spring integration test?

The `perform()` method is used to call a GET request method, ultimately returning the *ResultActions*.

## Things I want to know more about

Testing in general, I feel like theres a lot more to this.
