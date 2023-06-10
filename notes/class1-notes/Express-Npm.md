# Readings: Express, NPM, TDD, CI/CD

This section matters because it's an introductry way to understand building websites using Node.js, using the express  which is the most famous node web framework that allows us to deal with more flexibility while building APIs.

## ***An introduction to NodeJS and Express***

 ***1- Explain middleware, answer as though I were a non-technical recruiter.***

>Middlewares are bunch of code lines that performs a process, we use them as a process interfering order based on an order we specify, they are like an extra pieces of lego we put inside the whole structure to give a better appearance (while in coding more prefernece functionality), they affect the way the user see or send information from and to the servers.

 ***2- Express the most popular ____ __.***

> Node web framework.

 ***3- Express is “unopinionated.” What does that mean?***

> it means that there is no strict certain syntax or way to type express code to operate a task, there are multiple way that could get the job done eventually (more freedom).

 ***4- What is a module and why is modularity useful to us as developers?***

>simply it is a re-usable JavaScript code in seperate files that could be exported, then imported and used in a different JavaScript file too. THEY ARE MODULES OF CODE! and their importance is instead of re-inventing code lines that do the same functionality, we just import them from a person who already did it!.

---

## ***NPM***

 ***1-What version of npm are you running on your machine?***

> 9.6.6

 ***2-What command would you type to install a library/package called ‘jshint’ into your node project?***

> `npm install jshint`

---

## ***TDD***

 ***Explain why tests are important. Please explain as though I were your non technical elder.***

> test driven development is a process like giving an exam or an interview for an indivdual, and once he/she passes it, then it's decided that that person is suitable to work. this concept is the same applied on program application, where the application writers type a test that defines the needed requirements of the final product, and once "under-development" program passes all the test, it is ready to use. So we conclude from that the importance of TDD is to make a product free of erros, and written in the simplest way since the exam could be solved in different ways that could be chosen.

 ***What are three expected benefits of testing***?

> - Less errors and app failures with the same effort used to build that product
> - the spent time on making these tests will be compensated at the final stages of making the product (more errors avoided, less erros to appear at end stage)
> - A higher quality end product

 ***Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.***
>
 1- Individual pitfalls:

 > - forgetting to run tests frequently
 > - writing tests that are too large or coarse-grained
>
 2- Team pitfalls:

 > - partial adoption – only a few developers on the team use TDD
 > - poor maintenance of the test suite – most commonly leading to a test suite with a prohibitively long running time

 ---

## ***CI/CD***

  ***What are three benefits of Continuous Integration?***

There are multiple benefits of CI which of are:

> - Saving time, by allowing a whole team to work on the functionalities/desgin (whole production) of an app.
> - Delivering code in smaller pieces which make it easer to track and easier to debug.
> - Automated testing for each integrated part the team worked on which reduces the costs as well.

***What is the difference between Continuos Delivery and Continuous Deployment?***

 >Simply Continuos Delivery is meant to test the ready developed code for being ready to deploy in the backstage by automated testings on it so it will be ready before real deployment, while Continuous Deployment is taking that tested code which reached from the Continuous delivery phase and deploy it as a production usually in automatic way.

 ***Explain how GitHub fits into this process assuming the listener comes from a non-technical background***

 >Github allows for making test after each editing on the code, also it allows us to work in teams to develope a whole working product, and once each part is integrated, it give us the results of testing and tell us if there is an error or not before accepting the code and pass it to the next process of production. also using github pages, once your code is deployed, and once you edit the code and develop it for the next level, if the code passes the pre required tests it will be re-deployed with the new content on that page you already created, so github offers both stages of CI and CD.

## Reflection

***What are your learning goals after reading and reviewing the class README?***

>The goals are to implement and understand the concepts we will learn such as  using and creating Modules by Node, understand and use middlewares using express, differntiate between status codes with each response, apply the TDD approach while building our applications.

---

## Things I want to know more about

I would like to be understand better how requests works, also want to understand better how Express.Router works exactly.

---
