# Redux using Angular framework

Creating State for Products in Redux

- Run npm install for installing dependencies.
- Run ng serve for a dev server.
- Navigate to http://localhost:4200/. 
The app will automatically reload if you change any of the source files.

Redux organizes your application state in the store, a single data structure in your application. The components of your application read the state of the application from the store. The store is never mutated directly. Instead a action is dispatched to a reducer function. The reducer function creates a new application state by combining the old state and the mutations defined by the action.


**Store**
The store is a single JS object. To create a store you simple need to a add a TypeScript file to the project and declare a new interface type which contains all the properties you’d like to keep in the store.

**Actions**
Actions are plain JS objects that represent something that has happened. Can be compared to events.

**Reducers**
A reducer is a function that specifies how the state changes in response to an action.
What’s important to understand is the fact that a reducer function does not modify the state. It always returns a new state object with the modifications included.
A reducer function must always be a pure function. That means that the function must ensure that if the same input is given always the same output is produced.


