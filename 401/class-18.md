# Day 18 Reading Notes

## Identity
- ASP.NET Core Identity is a membership system that adds login functionality to ASP.NET Core apps.
- Users can create an account with the loign information stored in Identity or use an external login provider like google or facebook
- Identity can be configured using a SQL Server database to store user names, passwords, and profile data. Alternatively, another persistent store can be used, for example, Azure Table Storage.
- There are three classes which represent the identity of a user: Claim, ClaimsIdentity, and ClaimsPrincipal

### Claims

  - A Claim represents a single fact about the user. It could be the user's first name, last name, age, employer, birth date, or anything else that is true about the user.

  - A single claim will contain only a single piece of information. A claim representing something about a user John Smith could be his first name: John. A second claim would be his last name: Smith.

  - Claims are represented by the Claim class in ASP.Net Core. It's most common constructor accepts two strings: type and value

### ClaimsIdentity

- An Identity represents a form of identification or, in other words, a single way of proving who you are.

- In ASP.Net Core, it is a ClaimsIdentity. And represents a single form of digital identification.

### ClaimsPrincipal
- A Principal represents the actual user. It can contain one or more instances of ClaimsIdentity, just like in life a person may have a driver's license, concealed-carry permit, social security card, and a passport

- Each of the identities is used for a different purpose and may contain a unique set of claims, but they all identify the same user in some form or another.

- 
### Things I Want To Know More About:


### My Sources:
- https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-2.1&tabs=visual-studio
- https://digitalmccullough.com/blog/aspnetcore-auth-system-demystified/

[Back to Main](README.md)