# Day 14 Reading Notes
## Routing within MVC

In the StartUp:

ASP.NET Routing is enabled in your application's Web configuration file (Web.config file)

 routes.MapRoute(

                "Default",
                                                             
                "{controller}/{action}/{id}",                           
                new { controller = "Home", action = "Index", id = "" } 
Example:

 /Home/Index/3

controller = Home

action = Index

id = 3

When you request the URL /Home/Index/3, the following code is executed:

HomeController.Index(3)

### Routing Within Core
- Routing is responsible for matching incoming HTTP requests and dispatching those requests to the app's executable endpoints
-  Endpoints are the app's units of executable request-handling code

In the StartUp:

app.UseEndpoints(endpoints =>
{
    endpoints.MapGet("/hello/{name:alpha}", async context =>
    {
        var name = context.Request.RouteValues["name"];
        await context.Response.WriteAsync($"Hello {name}!");
    });

- The string /hello/{name:alpha} is a route template. It is used to configure how the endpoint is matched. In this case, the template matches:

- {name:alpha} bound to the name parameter.

Calling UseAuthentication and UseAuthorization adds the authentication and authorization middleware. These middleware are placed between UseRouting and UseEndpoints so that they can:


### Things I Want To Know More About:


### My Sources:
- https://docs.microsoft.com/en-us/aspnet/mvc/overview/older-versions-1/controllers-and-routing/asp-net-mvc-routing-overview-cs

- https://docs.microsoft.com/en-us/aspnet/core/fundamentals/routing?view=aspnetcore-5.0

[Back to Main](README.md)