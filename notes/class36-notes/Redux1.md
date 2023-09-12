# Application State with Redux

## Dan Abramov Redux Tutorials

**What is the first principle of Redux?**

>The first principle that all the states of my application will be saved and managed inside one state object, usually called states tree.

**What is a store and what do we use our reducers for within that store?**

    Store is a utility inside redux that holds the three redux principles together, holding the state tree, the dispatches and the reducer function that will describe how to mutate the state.

**Name three Redux store methods given to us by createStore and describe their use.**

>getState() it returns the current state of the application state tree that is saved by redux

>subscribe() it allows you to save a callback function that will run on every dispatch happens by the reducer.

>dispatch() it allows you to dispatch events or lets say actions that describe the minimal change of the state which will end by updating the state.

**Explain to a non-technical recruiter what combineReducers() does and why it is useful.**

>Imagine that you have 3 pens each with a type and size, instead of finding a containter for each pen, you will create a container that can fit all the shapes of these pens and save them until use. so it's a way to save multiple things and reduce them into 1 thing that could be used the same way of using them individually.

## Things I want to know more about

More about Redux

