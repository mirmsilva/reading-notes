# Day 12 Reading Notes

## Entity Framework and APIs

- Entity Framework (EF) Core is a lightweight, extensible, open source and cross-platform version of the popular Entity Framework data access technology.
- Data access is performed using a model
  - A model is made up of entity classes and a context object that represents a session with the database
  - The context object allows querying and saving data

### Data Seeding

the process of populating a database with an initial set of data.

There are several ways this can be accomplished in EF Core:
- Model seed data
- Manual migration customization
- Custom initialization logic

### User Secrets
A secure way of storing private user information such as API keys, client secrets, and connection strings. Anything that you don’t want others to know about when using your code base.


### Things I Want To Know More About:


### My Sources:
- https://codefellows.github.io/code-401-dotnet-guide/resources/user-secrets.html
- https://docs.microsoft.com/en-us/aspnet/core/data/ef-rp/intro?view=aspnetcore-2.1&tabs=visual-studio
- https://docs.microsoft.com/en-us/ef/core/modeling/data-seeding
- https://docs.microsoft.com/en-us/ef/core/
- https://docs.microsoft.com/en-us/aspnet/core/data/ef-mvc/intro?view=aspnetcore-5.0
- https://www.youtube.com/watch?v=aIkpVzqLuhA

[Back to Main](README.md)