# Day 8 Reading Notes

## API Design Best Practices

- What does REST stand for?
  - Representational State Transfer

- REST APIs are designed around a ____.
  - resources

- What is an identifer of a resource? Give an example.
  - A URI https://miriam-silva.com/cats/zoey
- What are the most common HTTP verbs?
  - GET, POST, PUT, PATCH & DELETE
- What should the URIs be based on?
  - should be based on nouns (the resource). And not the verbs (the operators on the resource)
- Give an example of a good URI.
  - https://adventure-works.com/orders
- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
  - When API's expose a large number of small resources. It's a bad thing that may require the client to send mulitiple request to get all the information it needs
- What status code does a successful GET request return?
  - HTTP status code 200 (OK)
- What status code does an unsuccessful GET request return?
  - 404 (Not Found).
- What status code does a successful POST request return?
  - HTTP status code 201 (Created)
- What status code does a successful DELETE request return?
   - HTTP status code 204

[Back to Main](README.md)

### My Sources:
- https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design