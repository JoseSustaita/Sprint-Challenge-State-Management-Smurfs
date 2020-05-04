1. What problem does the context API help solve?

   Context API helps solve the problem of prop drilling and passing props to multiple levels of components.

1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions: send data from the app to the store

Reducers: Help update the state based on the actions sent to store

Store: Is immutable state that holds the main state of the application

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?

App state is global state whereas component state is local. Use application state when you want to the whole application to have access to the state and use componenet state when you only want a specific component to have access to the stae.

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

redux-thunk allows you to write action creators. The actions creators then are returned as functions

1. What is your favorite state management system you've learned and this sprint? Please explain why!

Favorite is Redux, a lot of it is broiler- plate code but once you get used to that it can be very helpful to implement into large scale applications.
