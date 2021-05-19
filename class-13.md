# Day 13 Reading Notes

## Local Storage

Web applications do not have a great way to to store data. One way they work around that is to use cookies.

Cookies can store small amounts of data but have some downsides:
- because they are included with every http request they slow your web browsing. 
- they send unecrypted data over the internet
- they are limited to 4kb

Other ways to store data were either specific to a browser or reliant on third parties

## HTML5 Storage

it's a way for web pages to store named key/value pairs locally  within the client web browser. The data will persist even after you navigate away from the site. Unlike cookie data the information is never transmitted to the remote server.

### How to Use
Since it is storage based on named key/value pairs. you store data on a named key then retrieve it with the same key.

The named key is a string. Use Parse or Int is you need to retrieve anything other than strings

You can keep trak of changes to the HTML5 Storage area by setting up an event.

### Limitations

You are storing strings. Not data in its original form

Each digit is stored as a character.

You cannot ask for more storage space past the 5mb.


[Back to Main](README.md)