# AWS: Events

## AWS SQS vs SNS

What is the difference betweeen SQS and SNS?
>Simple Notification Service (SNS) is a Publish-Subscribe service, it's like messaging service that allow you to send messages for those who subscribed for that service easily and effectively for example messages on e-mails or SMS. it's also has the entity type of Topic-Subscriber.

>Simple Queue Service (SQS) is a Queueing service, it's an other way of recieving temporary message max(14 days) on request, so unlike notifications, these queue are requested so you could get an answer back as a message.

What are some use cases for both SNS and SQS?

>for SNS: use it for multiple subscribers, many more message to send and parallel send of messages.

>for SQS if you are going to send messages between two applications who are connected for a while, for less amount of subscribers.

## AWS SNS and SQS

Describe how to use SQS and SNS in a “fanout” pattern.

>The fanout approach or pattern, is like distributing an event for mulitple directions, to get different reactions of functions and processes happen in multidirectional way with different responses, like using SNS to push a notification for 3 different subscribers, lets say each subscriber is in a different role of job, some would care about it and react and some wouldn't but keep it to read later for example.

Explain how “push notifications” work, using SNS.

>The push system means that you have an event to distribute, for whoever insterested of that event news, must subscribe to the event distributer so once a new event occur, a message will be pushed(sent) to all subscribers notifying them of that new event ocurring.

## SQS and SNS Basics

How might a large scale, distributed application make use of a Queue system like SQS?

>fFor highly scalabe applications, it is hard for the server devices sometimes to handle the large scaling amount of requests as messages from events or just pure requests, so using SQS, as a temporary durable containter that would order and organize these traffics of messages inside them, and especially with FIFO queue types where it protect from duplications, it will make like a middle ware between the server and the client side, and organize what's go in and out in a fast yet persistent organized way not causing erros of throttling from the database or the server.

## Things I want to know more about

>To know how to link my SNS or SQS to my application or Lambda function that would result in a notifcations system by one of the messaging methods.
