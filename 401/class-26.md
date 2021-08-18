# Day 26 Reading Notes

## Intro to MVC

- MVC is a design pattern or architecture which helps develop web applications in an efficient way
- **M** Model : represents the objects in our application.  Think of it as a class with all objects and their properties & methods
- **V** View : the UI, here you will find the html controls
- **C** Controller : handles the requests from the user & returns a response by loading the appropiate View with data from the model

## Tag Helpers

- They enable server-side code to participate in creating and rendering HTML elements in Razor files. 
- There are many different types of tag helpers for tasks such as creating forms, links, or loading images
- It looks like standard HTML and allows us to edit Razor without learning C# Razor Syntax
- Tag Helpers scope is controlled by a combination of @addTagHelper, @removeTagHelper, and the "!" opt-out character.

### Things I Want To Know More About:

- I am excited to start incorporatin bootstrap in our Labs

### My Sources:
- https://www.c-sharpcorner.com/article/learn-basics-of-mvc-architecture/

- https://docs.microsoft.com/en-us/aspnet/core/mvc/views/tag-helpers/intro?view=aspnetcore-2.1


[Back to Main](README.md)