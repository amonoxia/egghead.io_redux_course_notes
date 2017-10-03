Quick Summary and Cheatsheet
For beginners. See the rest of the notes for explanations, transcript and code examples.

# Three Principles of Redux
1. The entire state of the application will be represented by one JavaScript object.
2. The state tree is read-only.
3. The Reducer function takes the previous state of the app and action being dispatched and returns the next state.

# Other Things to Know
a. When writing a reducer, if state is not defined, return an object representing the initial state.
b. Use `expect` library to make assertions.
c. Include into `<div id='root'></div>`

# Functions

## Store Methods
`getState()     // built in to redux; retrieves current state of store`
`dispatch()     // how to dispatch actions to change the state`
`subscribe()    // registers a callback to update the UI to reflect current state after a dispatched action`

# Syntax Used
`function name_of_function()      // function`
`const name_of_element`
`const store = createStore(name_of_store);   // createStore`

# Glossary/Things to Google
change listeners
prop
dumb component - specifies how the current state is rendered into output, and how the callbacks passed via props are bound to the event handlers
