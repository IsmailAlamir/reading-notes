# Readings: Django REST Framework & Docker


## REST Framework 
- Django REST framework is a powerful and flexible toolkit for building Web APIs.
- reasons to know more about REST framework
  - reasonsThe Web browsable API is a huge usability win for your developers.
  - Authentication policies including packages for OAuth1a and OAuth2.
  - Serialization that supports both ORM and non-ORM data sources.
  - Customizable all the way down - just use regular function-based views if you don't need the more powerful features.
  - Extensive documentation, and great community support.
  - Used and trusted by internationally recognised companies including Mozilla, Red Hat, Heroku, and Eventbrite.


## Beginner’s Guide to Docker

Docker is a way to isolate and run entire applications.

### Conclusion

- Docker is a way to run Linux containers
- Containers are a lightweight alternative to Virtual Machines
- ***Dockerfile*** is a list of instructions for creating an image
- Images are made up of one or more layers
- Containers are a running instance of an image
- ***docker-compose.yml*** controls how to run the container
- Containers are stateless and ephemeral in nature. We can link the local filesystem via ***volumes*** but things become more complex with databases.

### Traditional Django

A traditional Django website consists of a single project with multiple apps representing discrete functionality. 

> First app
> Models
> Admin
> Views
> URLs
> Templates
> Tests
> Git
> Docker architecture 

![image](https://docs.docker.com/engine/images/architecture.svg)
