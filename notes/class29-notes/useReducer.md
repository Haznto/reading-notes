# useReducer()

## Extracting State Logic into a Reducer

***What is the motivation for adding a reducer?***
>When your application and specifically your component scales up in terms of using many useStates() it will end up hard to trace when a bug arises and will be more complex to read. here where it comes to play to use the Reducers.

***What are actions in the context of a reducer? How are they different than setting state directly?***

>Actions are more like the events descriptions, mainly what the user did do that will request the state to be updated, so actions describe the event as dispatches of objects that will be send to the reducer, and based on the description of that action, you will specify the logic to execute based on that action to change the current state.

***What common list operation is useReduce named for, and why?***

>It's the reduce method of arrays, where you start with a current value that keeps updating until the end of that operation, which is actually happening behind the scene by react updating the state.

***When should you switch from useState to useReducer?***

>if a there is a pile of useStates inside my components I would transfer them to an isolated reducer to manage my code better and make it readible, which will help debugging it and also for testing it.

## Things I want to know more about

making custom hooks.
