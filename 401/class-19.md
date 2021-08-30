# Day 19 Reading Notes

### Claims-based authorization in ASP.NET Core

- A claim is a name value pair that represents what the subject is, not what the subject can do
- An identity can contain multiple claims with multiple values and can contain multiple claims of the same type.
- Code for startup: 

public void ConfigureServices(IServiceCollection services)
{
    services.AddMvc();

    services.AddAuthorization(options =>
    {
        options.AddPolicy("EmployeeOnly", policy => policy.RequireClaim("EmployeeNumber"));
    });
}

### Authorization & Authentication

- Authentication is the process of determining who you are
- Authorisation revolves around what you are allowed to do, i.e. permissions

### JWT

- JSON Web Token (JWT) is a means of representing claims to be transferred between two parties. aka, another way to encode JSON objects as access tokens

### Things I Want To Know More About:
- https://docs.microsoft.com/en-us/aspnet/core/security/authorization/claims?view=aspnetcore-2.1
- https://andrewlock.net/introduction-to-authentication-with-asp-net-core/
- https://codeburst.io/jwt-to-authenticate-servers-apis-c6e179aa8c4e

### My Sources:


[Back to Main](README.md)