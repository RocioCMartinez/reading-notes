# Class 11 Reading

## [Spring App Basics](https://spring.io/guides/gs/serving-web-content/)

What role do the @Controller classes play in a Spring MVC application?

It is a controller that handles GET requests.

Explain to a non-technical friend what a GET request is.

I think of GET, as "Get me that information please so I can look at it". It is an internet request to an API to retrieve information for the purpose of reading and displaying it.

What annotation should be placed on your Spring Boot application class?

@SpringBootApplication - will help add configuration tags, enabless auto configurtion among other things.

## [Spring MVC and Thymeleaf](https://www.thymeleaf.org/doc/articles/springmvcaccessdata.html)

What method allows for a variable defined in Java (in your Spring Controller) to be dispalyed in HTML with the help of Thymeleaf?

A model map created from the @Controller class.

Explain the role of a @Controller class in a Spring MVC application.

The role of the @Controller class is to prepare model map data and making requests.

What is a model attribute refered to in Thymeleaf?

A model attribute is what Spring MVC calls the pieces of data that cn be accesed during the execution of views. In Thymeleaf language known as *context variables*.
