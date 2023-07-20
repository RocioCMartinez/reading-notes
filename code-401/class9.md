# JAVA & HTTP

## [Review: High-level HTTP](https://dev.to/dangolant/things-i-brushed-up-on-this-week-the-http-request-lifecycle-)

What are the five steps in the HTTP Request Lifecycle?

- Step1: Local Processing
- Step2: Resolve an IP
- Step3: Establish a TCP Connection
- Step4: Send an HTTP Request
- Step5: Tearing Down and Cleaning up

What are the two things the client needs before it can make an HTTP Request?

An IP address and a TCP connection.

Explain the four way handshake and what it does.

The four way handshake explainsthe TCP connection process. Fist a response must be fully delivered, the client will send a FIN packet, the server will respond with ACK and send a FIN, finally the client respondswith an ACK.

## [Java HTTP Request example](https://www.baeldung.com/java-http-request)

True or False: When making an HTTP request, you MUST follow any redirect returned by the request. Back up your answer.

This is both true and false. You will be presented (if it exists) with a new location to the content you were aiming for. You can decide to take the new path provided, I would aim to inspect the http and ensure it is still related to the content you are looking for.

Which built-in Java class can be used to perform an HTTP request?

HttpUrlConnection (HttpClient API)

What HTTP status codes represent a successful response? A redirect? A client error?

- Successful response: 200 (OK) typically 2XX
- Redirect: 301 (Found) typically 3XX
- Client error: 400 (Bad Request) typically 4XX

## Things I want to know more about

Seeing HttpUrlConnection in practice, it would help with understanding. Maybe I can find a YouTube video on this.
