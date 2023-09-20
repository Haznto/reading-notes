# Redux - Additional Topics

## Redux Toolkit (RTK)

***What concerns are addressed by Redux Toolkit?***

>Configuring redux store is too complicated, many packages to get the job done using redux, and it need extreme boilerplate code.

***What does configureStore() do?***

>The same as createStore but more enhanced, you can define your reducers as slice controllers of certain whole state slice, and this configureStore automatically manage it and combine them in addition to middleware such as thunks.

***How would I use createSlice()?***

>You start by importing it, then use it to accept an object of entities, the name of the slice, it's initial state and the reducers responsible to control that slice of state.

## MobX

What is Mobx?
>State manangement tool as redux but it addresses most of the important issues that came up from the state being immutable, so this Mobx gurantee to produce a consistent state.

How does MobX make it “impossible” to produce an inconsistent state?

>- use the observable decorator or observable(object or array) functions to make objects trackable for MobX
>- The computed decorator can be used to create functions that can automatically derive value from the state and cache them.
>- Use autorun to automatically run functions that depend on some observable state. This is useful for logging, making network requests, etc.
>- Use the observer wrapper from the mobx-react-lite package to make your React components truly reactive. They will update automatically and efficiently. Even when used in large complex applications with large amounts of data.

How would we build a reactive user interface?

>Develop React components that refresh automatically upon relevant data modifications. Employ the observer higher-order component (HoC) provided by either the mobx-react or mobx-react-lite package to imbue your React components with reactivity.

What take-away(s) did this tutorial provide?

>It only addresses how to build up and manage the store using redux toolkit instead of redux alone. which makes it easier to deal with.

