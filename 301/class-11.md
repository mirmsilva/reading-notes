# Day 11 Reading Notes

## What is OAuth

- What is OAuth?
  - an open-standard authorization protocol that describes how unrelated servers and services can safely allow authenticated access to thei assets without sharing the initial, related, single logon credential
- Give an example of what using OAuth would look like.
  - going to a website and logining in with another website authenticating you. Like using facebook to authenticate who you are on a different website
- How does OAuth work? What are the steps that it takes to authenticate the user?
  - the first website connects to the second on behalf of the user. 
  - the second webiste generates a one time token & secret unique to the transaction
  - the fisrt site gives the token & secret to the users's client software
  - the client's software presents the request token & secret to their authorization provider
  - the client maybe be asked to authenticate & approve the authorization
  - the user approves
  - the user is given an approved access token
  - the user gives the toke to the first website
  - the first website gives the access token to the second website
  - the second website lets the first site access their site on behalf of the user
  - the user sees a successfully completed transaction occurring
- What is OpenID?
  - OpenID is for user authentication

## Authorization and Authentication flows

- What is the difference between authorization and authentication?
  - athorization is approval and authentication is verification
- What is Authorization Code Flow?
  - Exhanges an authorization code for an access token
- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
  - mobile & native applications can use Authorization Code Flow but require additional security
- What is Implicit Flow with Form Post?
  - It is intended for public clients or applications which are unable to securely store Client Secrets
- What is Client Credentials Flow?
  - machine to machine applications or services on your backend the system authenticates and authorizes the app rather than the user
- What is Device Authorization Flow?
  - with input constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smatphone and authorize the device
- What is Resource Owner Password Flow?
  - requests that users provide credentials (username & password), typically using an intercative form


[Back to Main](README.md)

### My Sources:
- https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html
- https://auth0.com/docs/flows