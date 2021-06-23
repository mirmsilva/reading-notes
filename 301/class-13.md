# Day 13 Reading Notes

## Status Codes Based On REST Methods

- In your own words, describe what each group of status code represents:
  - 100’s = The server received the request, will try to execute the request but, it will likely fail
  - 200’s = Success!
  - 300’s = The thing you are looking for has moved
  - 400’s = The request made by the client was invalid
  - 500’s =  Server error. They could just be overwhelmed so try again later
- What is a status code 202? 
  - Accepted. Used for asynchronous processing
- What is a status code 308? 
  - Permanent Redirect. Use a different URL
- What code would you use if an update didn’t return data to a client?
  - Code 204 No Content
- What code would you use if a resource used to exist but no longer does?
  - Code 204 No Content
- What is the ‘Forbidden’ status code?
  - Code 403

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  - When we deploy we don't want to use the local host
- What is middleware?
  - code that runs when a server gets a request
- What does app.use(express.json()) do?
  - accepts Json as the body
- What does the /:id mean in a route?
  - its a parameter that gives you access to that specific item
- What is the difference beween PUT and PATCH?
  -  Put is creating, Patch is updating
- How do you make a default value in a schema?
  - default: 
- What does a 500 error status code mean?
  - There's an error on your server. It had nothing to do with the client
- What is the difference between a status 200 and a status 201?
  - 201 sucessfully created something. 200 is more general success

[Back to Main](README.md)

### My Sources:
- https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/
- https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw