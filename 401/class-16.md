# Day 16 Reading Notes

### DTOs
A DTO is an object that defines how the data will be sent over the network

Web APIs can expose the database entities to the client. The client receives data that maps directly to your database tables. However, that's not always a good idea. Sometimes you want to change the shape of the data that you send to client

The biggest advantage of using DTOs is decoupling clients from your internal data structures

Think about them as a presentation layer that allow you to hide sensitive information from the client/internet(like a password, birthdate)

Things I Want To Know More About:

My Sources:

- https://www.infoworld.com/article/3562271/how-to-use-data-transfer-objects-in-aspnet-core-31.html
- https://docs.microsoft.com/en-us/aspnet/web-api/overview/data/using-web-api-with-entity-framework/part-5

[Back to Main](README.md)