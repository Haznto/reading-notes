# Redux - Combined Reducers

## Multiple Reducers Example

***Why create multiple reducers?***

>It's like the concept of components, why building 1 html file that contains everything and when you want to edit it or re-use it, it will be almost impossible to do that, same as multiple reducer, you can make many reducers and each could change a single part of the current state, and when you want to update how that part is changed, you only navigate to the reducer file that is responisble for this change.

***How would you combine multiple reducers?***

>using a method of redux called combineReducers() that will accept an object of reducers.

***How will you manage state as an immutable object? why?***

>You always have to manage it as immutable by overwriting the whole state with the new one that has a certain small change, not directly updating the target and returning the same state that was updated, because this manner will gurantee you that no conflicts will happen to the state on several dispatches.

## Redux Docs: Using Combined Reducers

***combineReducers is a utility function to simplify the most common use case when writing ___ _____ .***
> Redux reducers

***Explain how combineReducers assembles the new state tree.***

>It uses the approach of slicing, you cut the whole state into smaller pieces and assign each reducer to manage that piece, so it will be easier to manipulate the state, and you also can assign action types with same type for multiple slices within different reducers and they will act seperately, so for example you have two slices of data, username and comment, and you want to change the state of these two into something new, u could assign two reducers, with two same action types, when will manipulate the username and the other will manipulate the comment once the action is dispatched.

***How would you define initial state in an app using combineReducers?***

>First, the createStore function can take preloadedState as its second argument. This is primarily intended for initializing the store with state that was previously persisted elsewhere, such as the browser's localStorage. The other way is for the root reducer to return the initial state value when the state argument is undefined.

## Redux Docs: Combined Reducer Syntax

***Why will you want to split your reducing functions as your app becomes more complex?***

>as answered before to make things easier and simpler to manage.

The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.
> combineReducers, createStore.

What is a popular convention when naming reducers?

>To name the reducer based on the slice name that the reducer is managing, for example if you want to update the username mentioned above, it's better to name that reducer with such functionality the same.

## Things I want to know more about

How to use store.dispatch and other non-legacy methods instead of the old ones.
