# Module 3 Class 12 Reading Notes

## CRUD

### Status Codes

- 100’s = informational
- 200’s = success
- 300’s = redirection
- 400’s = client error
- 500’s = server error

### What is a status code 202?

Processing valid request

### What is a status code 308?

Permanent redirect

### What code would you use if an update didn’t return data to a client?

204

### What code would you use if a resource used to exist but no longer does?

410

### What is the ‘Forbidden’ status code?

403

## Building a REST api with Node.js, Express & MongoDB

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

Because it contains a password which should be kept private.

### What is middleware?

Code that runs when the server gets a request but before it gets passed to the routes.

### What does app.use(express.json()) do?

It sets the server up to accept json

### What does the /:id mean in a route?

It represents the id part of the url

### What is the difference between PUT and PATCH?

PUT updates the whole resource, whereas PATCH partially updates the resource.

### How do you make a default value in a schema?

```
const schema = new Schema({
  name: String,
  role: { type: String, default: 'guitarist' }
});
```

### What does a 500 error status code mean?

The server encountered an unexpected condition that prevented it from fulfilling the request.

### What is the difference between a status 200 and a status 201?

200 - everything is OK.
201 - new resource created.
