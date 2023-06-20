# CRUD

## Status Codes Based on REST Methods

In your own words, describe what each group of status code represents:

100’s = This is an informational code. Checks request with the header part and notifies of issues before taking in more data.

200’s = A sucess code. Tells the client they have a valid request.

300’s = Redirection codes. The location of resource is no longer valid. Must issue request to new location.

400’s = Cliend error codes. Occur for invalid requests from client to server.

500’s = Server error codes. May be caused by unreachable servers or general issues  with server.

What is a status code 202?

 Asynchronous processing of a request.

What is a status code 308?

 Code that indicates a new location for resource, at this point a new URL is provided.

What code would you use if an update didn’t return data to a client?

 204 No Content code.

What code would you use if a resource used to exist but no longer does?

 A 410 code for resurces that are gone.

What is the ‘Forbidden’ status code?

 403 no permission to access the resource.

## Build a REST API w/ Node.js, Express, & MongoDB

Why do we need to pull our MongoDB database string out of our server and put it into our .env?
What is middleware?
What does `app.use(express.json())` do?
What does the `/:id` mean in a route?
What is the difference between `PUT` and `PATCH`?
How do you make a default value in a schema?
What does a `500` error status code mean?
What is the difference between a status `200` and a status `201`?

## Responses

1. So that we can use an environment that is not our local host in the future.

2. Express is the middleware we use to link components. It is code that runs when the server gets a request but before its passed to your routes.

3. Allows the server to accept `JSON` as a body.

4. It means it is a parameter, we can have acess to what they type in after the /.

5. `PUT` updates all the information tht gets passed, while `Patch` is based on what the user passes us.

6. You can add a default key with the default value.

7. Means that there is an error with the server.

8. 200 is a general sucess code, where 201 specifies that something was created sucessfully (like an object).

## Resources

<https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/>

<https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw>
