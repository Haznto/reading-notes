# Event Driven Applications

This topic allows us to confine a more of a technique in our programming cascade, that will reduce the complexity and collision. since an application is full of events that are triggered when the user trigger that event. we call it event driven applications.

**What native Node.js module allows us to get started with Event Driven Programming?**

>*The ***events*** module once imported allows us to deal with event driven programming by accessing event emitter class, then create a new instance of that class.*

**What is the value of Object Oriented Programming used in tandem with Event Driven Programming?**

>*In OOP we are building functionality as seperate units (objects) then we use each one to communiacate with the other to make our whole application working, though as the application gets bigger and more complicated, it's challenging to keep importing and accessing or including (import) each functionality of an object inside another to use it, so instead we use event driven programming, where we define a function as an event emitter, and other function as listeners, once the listeners catch that emited  event, they will execute the functionality we need, so instead of importing each function multiple time, we emit it when an event happened due to another function.*

**Consider your knowledge of Event Driven Programming in the Web Browser, now explain to a non-technical friend how Event Driven Programming might be useful on the backend using Node.js.**

>It's like the law of "every action has a rection", this is how event driven programming work, we set these actions by coding our functionalities and we call them emitter, because they emit the action that will influence the reaction to happen. and the reactions will be listening, once that action happened they should react back!, Imagine that you want to boil water, your action is to heat the water using fire (the fire is the application processing) and you have your water (object) has a boiling point (the event emiiter ) , your water object will emit that event of boiling to it molecules(H2O are the listeners) and tell them, once my temperature reaches 100 (I emmit event ) listen to that event and react by boiling(reaction function).
---
>So Boiling point(Event Emitter) it the point of time when the Object(the source of the event) uses it's Molecules(Listeners) to perform an action (boiling) at that time.

## Things I want to know more about

Implemening DSA of Stack, Queue and Trees after learning them, into mock projects.

## What are your learning goals after reading and reviewing the class README?

To use event driven programming into our projects on the back end to make a wide new functionalities.
