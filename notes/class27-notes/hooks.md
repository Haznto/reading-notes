# useState() Hook

## Thinking in React

**Summarize the five steps of thinking in react.**

Step 1: Break the UI into a component hierarchy
> Break down the UI of your application into small pieces based on the best pattern you would find suitable that refers to your logic or background. make each component for example responisble about one functionality.

Step 2: Build a static version in React
>Represent your components with static data to start with at first, it is the best way of getting an idea how things will go on with dynamic data

Step 3: Find the minimal but complete representation of UI state

>Define what should be a state and what is not in you application, usually states are data that is independant and could be change multiple times overtime.

Step 4: Identify where your state should live
> Finding where the state should present, means the state changer, so you have to check all the components that are built using the change in data of that state and pick the parent or a component in a higher level above all these children to add the state changer in it, if not exist you can just create a component above them all for the state use only.

Step 5: Add inverse data flow
>Sending data upward the hierarchy, means to change the state by using the data coming from the children so the parent will render differently based on the events happening in the childrens.

## State: A Component’s Memory

**What is one reason a local variable isn’t sufficient for managing a React component?**

>Local variables don’t persist between renders.

**What is the argument to the useState hook, and what are the two parts of its return array?**

>The argument is only the initial value you start with for your variable

>It returns an array of The state variable & The state setter function.

**How can Component A access state from Component B?**

>States are isolated in nature, but moving the state from each component to the parent of both to keep them is sync, and to make the state accessible from on to another component, the state could be shared using props, passed down to a children.

**What are your learning goals after reading and reviewing the class README?**

>Make the right use of useState() hook.

## Things I want to know more about

> Learning about useEffect , useReducer and useRef.
