
## ES6 Classes

1- **Classes are a template for creating ____.**
>Creating objects

2- **Can a class declaration be hoisted?**

> Classes generally aren't hoisted meaning that you can't use classed before declaring them. in other definitions hoisted but with the temporal dead zone restriction.

3- **How would you describe a constructor and contextual “this” to a non-technical friend?**

> Classes are like rooms, and usually rooms got equipments (methods )inside it, one of these equipments is called constructor which is like a 3d printer inside that room to make and shape objects (referring to product) now also each product has features, using this inside that object in coding means that we are assigning a feature for that object we are creating. that feature in programming called (property).

## Express Routing

1- **Within Express, what does routing refer to?**

>Routing means the picking a path (endpoint) while navigating the application, picking a certain path will send a request to the server which will be answered with a response for the client.

2- **What is the difference between a route path and a route method?**

>The route method is a type of HTTP requests that defines the protocol of what should be sent back to the user as a response and how the request will be handles, examples are get, post, put, delete methods. While route path is the link(URL path) that will execute or invoke that method handling function once visited, it's like a trigger, once visited => requested it will trigger a function related to a certain HTTP method ending in a WRRC(web request response cycle.)

3- **When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?**

> **when there are multiple callback functions to handle the method request route, so we add next so each preceding function pass the executive process to the next one untill reaching the last one which doesn't necessirly need a next parameter in it since the functions are done. if you pass a next parameter to a function, you must pass that parameter inside that function but in invoked form ( next() )**

## Express Router

1- **What is an Express Router?**

>It's a class of express which can hold multiple HTTP methods inside it and middlewares , that's why sometimes it's called a mini app, so it's like a holder (modular) of many requests and related handler functions that could be exported and used again in another file.

2- **By what mean do we initialize express.Router() in an express server?**

>const router = express.Router()

3- **What do we use route middleware for?**

>Route middleware is used at the beginning of router, to initialize a process before even starting the request process, like authentication , retrieving data , logging data or any function that we would like to execute before initializing the WRRC .

## Reflection

>I am interested in learning more about express.router() and using it in exporting mini apps instead of writing each method and path seperately on a line and never use em again in another application.

## Things I want to know more about

>I would like to learn more in details about classes since we haven't been introduced to it before, and as I believe in will make every process easier since we can use multiple functionalities at once calling out that container (capsule of elements) called a class.
