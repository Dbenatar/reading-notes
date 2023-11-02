# APISs

What does REST stand for?
Rest stands for _Representational State Transfer_.

REST APIs are designed around a \_\_\_\_.
REST APIs are designed around any kind of object, data or service that can be accessed by the client. also known as _resources_.

What is an identifier of a resource? Give an example.
A resource has an idnetifier, which is a URI uniquely identifies that resouce. For example, when a customer is purchasing an item for a shop, their order will have a URI.

What are the most common HTTP verbs?
The most common HTTP verbs are **GET**, **POST**, **PUT**, **PATCH** and **DELETE**.

What should the URIs be based on?
URIs should be based on the resource(nouns) and not the operations (verbs) on the resource.
Give an example of a good URI.
https://starwars-shop.com/orders

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
A 'chatty' web API is a bad thing as this means the web server has many web requests imposed on it, meaning a bigger load on that server of small resources. This requires the client to send multiple requests to find all the data.

What status code does a successful GET request return?
A successful GET request typically returns status code 200.

What status code does an unsuccessful GET request return?
An unsuccessful GET request returns stus code 404
What status code does a successful POST request return?
A successful POST request typically returns status code 201
.
What status code does a successful DELETE request return?
A successful DELETE request typically returns status code 204.
