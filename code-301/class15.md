# Authentication

## What is OAuth

1. What is OAuth?
2. Give an example of what using OAuth would look like.
3. How does OAuth work? What are the steps that it takes to authenticate the user?
4. What is OpenID?

## Answers

1. OAuth is framework or open-standard authorization protocol. Safely allows authenticated acces without sharing the initial logon credential.
2. We have been using OAuth frequently in this class. An example would be logging in or authorizing actions on Render using Github.
3. It works when you are using 2 unrelated sites and use one to authorize the other.

- *"The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity."*

- *"The second site generates a one-time token and a one-time secret unique to the transaction and parties involved."*

- *"The first site gives this token and secret to the initiating user’s client software."*

- *"The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site)."*

- *"If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website."*

- *"The user approves (or their software silently approves) a particular transaction type at the first website."*

- *"The user is given an approved access token (notice it’s no longer a request token)."*

- *"The user gives the approved access token to the first website."*

- *"The first website gives the access token to the second website as proof of authentication on behalf of the user."*

- *"The second website lets the first website access their site on behalf of the user."*

- *"The user sees a successfully completed transaction occurring."*

- *"OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons)."*

4. OpenID is another security technology, but one that focuses on **authentication** and not authorization like OAuth.

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?
2. What is Authorization Code Flow?
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
4. What is Implicit Flow with Form Post?
5. What is Client Credentials Flow?
6. What is Device Authorization Flow?
7. What is Resource Owner Password Flow?

## Responses

1. Authoriztion is granting access, while authentication is proving ownership.
2. Code that exchanes an Authoriztion Code for a token.
3. It is the use of Authorization Code Flow plus a special challenge. ( I'm thinking this is the type the letters or find certain features in an image)
4. It is the alternative to Authorization Code Flow, not considered best practice, only needs an ID token to perform authentcation.
5. Where the system authenticates/authorizes the app rather than the user.
6. Where a link is sent to the user via phone or computer and they must got to the link for authentication.
7. Where users provide credentials typically using an interactive form, not recommended. Takes in the username and password.

## Resources

<https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html>

<https://auth0.com/docs/flows>

<https://auth0.com/docs/libraries/auth0-react>

## Things I want to know more about

Biometrics seems like the most secure way to authenticate is there a reason this is not not more popular? I'm guessing it might be due to collecting and storing that data.
