# Spring & Baeldung(JpaRepository)

## [Spring guide: Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)

How are query methods defined when using Spring Data JPA?

In Spring Data JPA, you can define query methods by declaring their method signature.

Which dependencies will you need in order to complete the Spring guide?

Spring Data JPA and H2 Database.

What annotations are used to specify an auto generated identification number for an Entity?

> The Customer object’s id property is annotated with @Id so that JPA recognizes it as the object’s ID. The id property is also annotated with @GeneratedValue to indicate that the ID should be generated automatically.

## [Baeldung: Comparing repositories](https://www.baeldung.com/spring-data-repositories)

Which of the Spring Data Repositories covered in the readings has the most methods available to it?

The JpaRepository.

Name a downside of a Spring Data Repository.

*"We couple our code to the library and to its specific abstractions, such as `Page` or `Pageable`; that's, of course, not unique to this library – but we do have to be careful not to expose these internal implementation details"*

How would you define an operation to find a student based on their name in a repo named StudentRepository which extends JpaRepository?

`public interface StudentRepository extends JpaRepository<Student, Long> {
    Student findByName(String name);
}`

## Things I want to know more about

I think for understanding purposes I would need to practice using these tools.
