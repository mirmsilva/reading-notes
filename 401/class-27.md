# Day 27 Reading Notes

## Views

- In MVC the view folder handles how the app will present data & hanlde user interaction
- It is an HTML template with embedded Razor markup that combined with the HTML markup produces a webpage that is then sent to the client
- VIew files should be grouped into folders named for each of the controllers with the main View folder placed in the root of the app
- The Home folder should contain views for the about, contact and index
- the Layout folder should provide consistent webpage sections & reduce code repetition. They often contain header, nav, menu and footer
- Partial views reduce duplicate code by managing reusable parts of views
- View Components are similar to Partial views in the they allow you to reduce repeating code but, require code to run on the server

### Benefits:

- App is easier to maintain due to the organization
- Parts of the app are loosely coupled.
- Easier to Test
- Less likely to have duplicate code

### How to specify Views:

The View helper method has several overloads. You can optionally specify:

- An explicit view to return:
  - return View("Orders");

- A model to pass to the view:
  - return View(Orders);

- Both a view and a model:
  - return View("Orders", Orders);

## Forms

- Forms can be weakly or strongly typed

- Weakly Typed Advantages:
  - They are easy to create
  - Used for one or two input items

- Weakly Types Disavantages:
  - IntelliSense will not help you 
  - Higher chance of exceptions & runtime errors

- Strongly typed allows to send objects therefore IntelliSense can help you

### Things I Want To Know More About:


### My Sources:
- https://docs.microsoft.com/en-us/aspnet/core/mvc/views/overview?view=aspnetcore-2.2

- https://www.completecsharptutorial.com/asp-net-mvc5/4-ways-to-create-form-in-asp-net-mvc.php

[Back to Main](README.md)