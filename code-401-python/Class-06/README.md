# What are Design Patterns

A design pattern is only a description or template for how to solve a problem!

### There is 3 major types of design patterns:
- Creational Patterns:
Creational patterns provide ways to instantiate single or groups of objects. Making it easier to create objects in a way that suits the situation.

- Structural Patterns:
Structural patterns provide a manner to define relationships between classes or objects. Making it easier for these entities to work together.

- Behavioral Patterns:
Behavioral patterns define manners of communication between classes and objects. Making it easier and more flexible for these entities to communicate.

# Risk Analysis
risk analysis is the process of identifying the risks in applications or software that you built and prioritizing them to test. The categorization of the risks takes place, hence, the impact of the risk is calculated.
### Risk Assessment :
In the risk analysis process, these steps prove to be the most important one. It is said that this step is way too complex and should be tackled with the utmost care. After risk identification, assessment has to be dealt programmatically.
#### The perspective of Risk Assessment:
- Effect : To assess risk by Effect. In case you identify a condition, event or action and try to determine its impact.
- Cause : To assess risk by Cause is opposite of by Effect. Initialize scanning the problem and reach to the point that could be the most probable reason behind that.
- Likelihood : To assess risk by Likelihood is to say that there is a probability that a requirement won’t be satisfied.

# Dependency Injection
dependency injection is a technique whereby one object (or static method) supplies the dependencies of another object. A dependency is an object that can be used (a service).

dependency in programming means:
When class A uses some functionality of class B, then its said that class A has a dependency of class B.

### There are basically three types of dependency injection:
1. constructor injection: the dependencies are provided through a class constructor.
2. setter injection: the client exposes a setter method that the injector uses to inject the dependency.
3. interface injection: the dependency provides an injector method that will inject the dependency into any client passed to it. Clients must implement an interface that exposes a setter method that accepts the dependency.

### Benefits of using DI
1. Helps in Unit testing.
2. Boiler plate code is reduced, as initializing of dependencies is done by the injector component.
3. Extending the application becomes easier.
4. Helps to enable loose coupling, which is important in application programming.


