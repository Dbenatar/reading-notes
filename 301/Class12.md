# CRUD

1.

100’s = These codes are informational status, used to tell the client that the header part of the requiest has been received. The server will then try to comply with a transmission demand of hte client.

200’s = These are the success codes that tell the client that a request was accepted. A 202 request, a asynchronous process request, shows this code not to say the request was sucessfully precessed but rather that it met all validation requirements.

300’s = Redirection codes that tell the client that the resource request isn't available at the expexted location anymore. There could be multiple reasons, some temporary or permanent, but hte client has to issue a request to the new location.

400’s = These are error codes which show hte incalid requests sent from the client to a server. These errors could be caused by a few different htings from timeouts, wrong URI or missing authentication.

500’s = These are a rannge of server error codes. These could be to indicatate problems with overwhelemd sercers or servers behind proxies which are unreachable. Sometimes these errors are related to a client requests that triggor error exceptions on the server.

What is a status code 202?
This code is often used for asynchronous processing and is a status code that tells the client the request was valid but its process will finish sometime in the future.

What is a status code 308?
This is the permanent redirect code that tells the client to use another URL to access the resource and not to use the current URL.

What code would you use if an update didn’t return data to a client?

What code would you use if a resource used to exist but no longer does?

What is the ‘Forbidden’ status code?

## REST API Node.js, Express and MongoDB

Why do we need to pull our MongoDB database string out of our server and put it into our .env?
What is middleware?
What does app.use(express.json()) do?
What does the /:id mean in a route?
What is the difference between PUT and PATCH?
How do you make a default value in a schema?
What does a 500 error status code mean?
What is the difference between a status 200 and a status 201?
