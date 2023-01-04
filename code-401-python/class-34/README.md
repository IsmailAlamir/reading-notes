# Context API
## What is Global State?
__global state__ refers to state that is shared across multiple components in an application and is not specific to any one component. 

It is a way of storing and managing data that is needed by multiple components, and it can be useful for keeping your components decoupled and making it easier to share data between them.

### Role of the global state
In React, originally, the state is held and modified within the same React component. In most applications, different components may need to access and update the same state. This is achieved by introducing the global states in your app. The main purpose of the global state is to share a state among multiple components.

There are three ways this communication can happen:

1. With a child component
2. With a parent component
3. With a sibling component


## Context API in React
__the Context API__ is a way to share data across the component tree without the need for props drilling (passing props down through multiple levels of components).

It allows you to create a context that can be accessed by any component that is a descendant of the context provider.

To use the Context API, you first need to create a context using the ```React.createContext``` function. This function returns a context object with a ```Provider``` component and a ```Consumer``` component. The ```Provider``` component is used to provide the context to the component tree, and the ```Consumer``` component is used to access the context from a descendant component.


## Context API vs Redux JS

__Redux__ is a JavaScript library for managing application state that provides a centralized store and a set of tools for defining the shape of the state, updating the state, and subscribing to state changes. It is often used in combination with React, but it can also be used with other libraries or frameworks. In a Redux application, you define the shape of your state and create a store using the ```createStore``` function, and you define reducer functions that specify how the state should be updated in response to actions.
____
To summarize
The Context API and Redux are both ways to manage state in a React application.

They have some similarities and some differences, and the choice between them depends on the specific needs of your application.


The Context API is a way to share data between components in a React application, while Redux is a library for managing global state in a React application. The Context API is simpler to use and requires less boilerplate code, but it is limited to managing state within a single component tree. Redux is more powerful and flexible, but it requires more setup and is better suited for managing global state. The choice between the two depends on the specific needs and requirements of your application.





