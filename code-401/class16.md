# Spring Security/Auth

Todays topic is about authentication and authorization. Distingushing between both and insight on the AuthenticationManager interface.

## [Spring Security Overview](https://spring.io/guides/topicals/spring-security-architecture/)

What does it mean to authenticate a user?

Authentication is varifying who someone is. Is the user a known user who can log in?

What does it mean to authorize a user?

Authorization is determining what they are allowed to do. What is the user allowed to do on the site?

What are the three possible outcomes of the AuthenticationManager’s authenticate() method?

>*An AuthenticationManager can do one of 3 things in its authenticate() method:*
>*Return an Authentication (normally with authenticated=true) if it can verify that the input represents a valid principal.*
>*Throw an AuthenticationException if it believes that the input represents an invalid principal.*
>*Return null if it cannot decide.*

## [Spring Auth Cheat Sheet](https://github.com/codefellows/seattle-java-401d2/blob/master/SpringAuthCheatSheet.md)
