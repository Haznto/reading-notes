# Component Based UI

## React Quick Start

**What are the building blocks of a React app?**

>Components are the building blocks of any React app.

**What is the difference between an HTML element and a React component?**

>A React component is a function that uses a special syntax of javascirpt, called JSX, these functions are meant to return html elements to be rendered, but the difference here that behind the scenes there is a transpiler changing the easy syntax we see inside the react component and transform it to a more acceptable JS syntax that could be implemented, using babel. So the HTML element in a React component isn't really a plain HTML element but a processed element.

**What is JSX and why do we use it?**
>It refers to JavaScript XML or JavaScript syntax Extention, it is used to write react components which are a composition of HTML/CSS/JavaScript all at once in easy syntax that will eventually render on the WebBrowser, transpiled by babel.

**Describe the process of embedding JavaScript expressions in JSX.**

>To embed a JavaScript Expression, you have to escape the JSX by using curly braces {} which allows you to start typing logic in plain JavaScript.

**Does React or JSX have any special features for iteration or conditional logic?**

>Since you escape the JSX syntax . there is no special feature of the logic in loops or conditionals, but what's special about react that you can use these conditionals and loops to manipulate what should be rendered on the screen, you can loop over an array of HTML elements to render them all in the page, or you can make a conditional based on a value to whether render a certain component or not.

**How does React know to respond to a user’s inputs?
What word indicates that a React component manages data with a Hook?**

>Using Hooks, for useState which is like enviromnital variables that change based on an event or invoked functions.
the 'use' word indicates we are initializing a hook.

**How can two react components share data?**

>Hooks such as useState has the ability to share the info between components just make your state on a higher level than the both components you want the info to be shared between and then pass the state as props for these children components.

## Render and Commit

**What are the three steps of refreshing a React UI?**

>Triggering,Rendering,Committing

**How do you trigger updates to a component after the initial render?**

>by changing it's state.

**Does React recreate DOM nodes on every rerender?**
>No, it only updates the minimal changes happening it certain parts of the dom based on double checks on the inputs and outputs of each component. if let's say the node has the same inputs it is expected to result in same output so the DOM won't do anything.

**After React has updated the DOM, what still needs to happen before the user sees the change?**

>it has to be rendered on the browser again, or in react it's called re-painting.

## Additional Questions

**Note the naming conventions in the Airbnb React/JSX Style Guide. What pattern(s) do you see?**

- Components naming should be PascalCased, while the instances of such components use camelCasing.

- Always files must match the naming of the components.

- Don't use props that are reserved words by the DOM itself.

- When importing files that are the root of a directory, just use the directory name to import it.

**Looking ahead at this module’s course schedule, What do you look forward to learning?**

>Mastering hooks.

**What are your learning goals// Things I want to know more about.**

Understand the differences between class based/ function based components and whether class components are still used or not.
