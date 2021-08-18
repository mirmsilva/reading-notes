# Day 28 Reading Notes

## HTTP Cookies

- An HTTP Cookie is a small piece of data that a server sends to the user's browser
- The browser stores it and sends it back later with other requests to the same server

Cookies are used for three purposes:

- Session management : Logins, Carts or anything else that the server should remember
- Personalization : User settings & preferences
- Tracking : Recording & analyzing behavior

- Because they are sent with every request they can slow down performance

To create a cookie:

- A server can send a Set-Cookie header with the response to the user.
- It is then stored in the browser and sent with any future requests
- It may have an expiration date
- May be limited to a specific domain

### Things I Want To Know More About:


### My Sources:
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies
- https://humanwhocodes.com/blog/2009/05/05/http-cookies-explained/
- https://asp.mvc-tutorial.com/httpcontext/cookies/

[Back to Main](README.md)