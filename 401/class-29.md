# Day 29 Reading Notes

## Cookies
An HTTP cookie (web cookie, browser cookie) is a small piece of data that a server sends to the user's web browser

Cookies are plain text; they contain no executable code

Used mainly for the following purposes:
- **Session management**
Logins, shopping carts, game scores, or anything else the server should remember

- **Personalization**
User preferences, themes, and other settings

- **Tracking**
Recording and analyzing user behavior

Cookies are sent with every request, so they can worsen performance (especially for mobile data connections)

Creating Cookies:

- The Set-Cookie HTTP response header sends cookies from the server to the user agent.
- Get-Cookie, with every subsequent request to the server, the browser sends back all previously-stored cookies to the server using the Cookie header.
- The lifetime of a cookie can be defined in two ways:
  -  **Session cookies** are deleted when the current session ends. The browser defines when the "current session" ends, and some browsers use session restoring when restarting, which can cause session cookies to last indefinitely long.
  - **Permanent cookies** are deleted at a date specified by the Expires attribute, or after a period of time specified by the Max-Age attribute.

- **Domain and Path** attributes define the scope of the cookie: what URLs the cookies should be sent to.

### Things I Want To Know More About:


### My Sources:
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies
- https://humanwhocodes.com/blog/2009/05/05/http-cookies-explained/
- https://asp.mvc-tutorial.com/httpcontext/cookies/

[Back to Main](README.md)