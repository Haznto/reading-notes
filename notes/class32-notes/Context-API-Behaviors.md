# Context API - Behaviors

## Scaling Up with Reducer and Context

**How do useReducer and useContext work together to simplify state management in a React application?**

*One of the best utilties to use together are useReducer & useContext, they are complementary for each others and makes the code much cleaner and easier to navigate through, since useReducers will cutoff the redundant use of useStates around the application and manage a bunch of states together in one file that is external from the component, the useContext come to play here and make the whole application has an access on all of these seperate reducers, which makes it efficient and more powerful to use the states, other than this, these states data will be saved outside the component so once the component re-render for example, the data is saved globally, no data loss will be lost, unless the whole application refreshes.*

*So in conclusion and simply, useReducer cut off the unnecessary use of useStates, and the useContext, will allow to access the shortcut of states(the reducers) everywhere in the application with the ability to temporary save the data in isolate place until the user refreshes the whole single page application. (Data saved globally).*

## Things I want to know more about

Redux
