#### What does REST stand for?
Representational State Transfer

#### REST APIs are designed around a resources.

#### What is an identifier of a resource? Give an example.
a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:
https://adventure-works.com/orders/1

#### What are the most common HTTP verbs?
GET, POST, PUT, PATCH, and DELETE

#### What should the URIs be based on?
nouns (the resource) 

#### Give an example of a good URI.
https://adventure-works.com/orders 

#### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
web APIs that expose a large number of small resources, and are not well structured try to avoid “chatty” web APIs

#### What status code does a successful GET request return?
A successful GET method typically returns HTTP status code 200 

#### What status code does an unsuccessful GET request return?
returns HTTP status code 404 (Not Found).

#### What status code does a successful POST request return?
returns HTTP status code 201 (Created).

#### What status code does a successful DELETE request return?
returns HTTP response code 200 (OK).
