# Module 2 Class 8 Reading Notes

## APIs

Source material: [Microsoft]("https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design")

### What does REST stand for?

Representational State Transfer

### REST APIs are designed around a \_\_\_\_.

Resources: i.e. an object, data or server that can be accessed by the client.

### What is an identifier of a resource? Give an example.

The identifier is a URI (Uniform Resource Identifier) that uniquely identifies the resource e.g. http://bike-website.com/bikes/3

### What are the most common HTTP verbs?

`GET`, `POST`, `PUT`, `PATCH`, `DELETE`,

### What should the URIs be based on?

The resource to be accessed

### Give an example of a good URI.

A good URI has a consistent naming convention.

http://bike-website.com/bikes/3

### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

A 'chatty' API is one where there are a lot of small resources, leading to a long URI which can add to the load on the server.

### What status code does a successful GET request return?

200 (OK)

### What status code does an unsuccessful GET request return?

404 (Not found)

### What status code does a successful POST request return?

201 (Created)

### What status code does a successful DELETE request return?

204 (No content)
