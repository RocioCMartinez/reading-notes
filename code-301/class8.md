# API Design

This reading covers the codes common to HTTP verbs which are helpful to know the status/troublshooting. We also look at APIs/URIs and how simplicity is key. You want to provide as much  informtion as possible in as few requests as possible.

## API Design Best Practices

1. What does REST stand for?
2. REST APIs are designed around a ____.
3. What is an identifier of a resource? Give an example.
4. What are the most common HTTP verbs?
5. What should the URIs be based on?
6. Give an example of a good URI.
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
8. What status code does a successful `GET` request return?
9. What status code does an unsuccessful `GET` request return?
10. What status code does a successful `POST` request return?
11. What status code does a successful `DELETE` request return?

## Answers

1. Representational State Transfer.
2. Resource, anything that can be accessed by the client.
3. An identifier is the URI, like <https://travel-works.com/bookings/1>
4. GET, POST, PUT, PATCH, and DELETE.
5. Nouns(the resource).
6. <https://bannanafeetdancecompany.com/classes>
7. Chatty is refering to a large number of small resources listed in the API. It is considered a bad thing because it would mean more requests, we must aim to put as much info into one request if possible.
8. Returns a 200 status code.
9. Returns a 404 (Not Found) code.
10. Returns a 201 (Created) code.
11. Returns a 204 (No Content) code.

## Resources

<https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design>

<https://regexr.com/>

<https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285>

<https://regex101.com/>

## Things I want to know more about
