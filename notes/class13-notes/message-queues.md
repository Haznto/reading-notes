# Message Queues

## Socket.io Chat Example

Explain to a non-technical recruiter what the Chat Example (above) does.

>That chat is like a quick postman, in the speed of millisecond he go to the post office (the server) to check for new mails (events) once found he will go and deliver the mail to the one has the name (the one acting to the triggered event). the postman is our socket.io, the post office is our server recieving info from users and save them as events content to eventually give them for the postman who can define who's mail is for who.

What proof of life are we getting on the backend from the above app?

>the proof of life could be two things, once a user open the path(route) we get a console.log message indicating that a user is connected to our server, the other is to console.log each message send by a user from that webpage.

Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

>broadcast method.

## Rooms

What is a room and how might a room be useful?

>a room is like a group of sockets, sharing a mutual channel that they can send events and all the sockets in that shared channel can get these events and listen to them, it will be helpful to make dependant routes with mututal events, or if you want to use it in chat, and you have a message to send for only the admins for example, you can add the admins as sockets to the room and send them this message only.

How do you join a room?
>using `.join` method after the socket object

how do you leave a room?
>using `.leave` method after the socket object

## Namespaces

What is a Namespace and what does it allow you to do?

>Namespaces are like subs of the main server, they act exactly like a server , having their own events, rooms and middlewares, they are like seperate channels to send and recieve events than the main server channel. but in reality they are using the same channel but different routing., it allows you to define which events certain users can access on different routes.

Each namespace potentially has its own what? (hint: 3 things)
>Rooms, events, middleware

Discuss a possible use case for separate namespaces

>Allowing certain users to access specific private events that represents special functionalities, so you make a namespace and allow certain authenticated users to connect with their authenticated sockets to that namespace to get benefit from it's functionalities. also you could make dynamic name spaces to allow each user on your website to have his own area to do his events that wouldn't affect other users profiles or events.

## Things I want to know more about

>Implementing them in real life applications and unserstand it in a simple way then practice it efficiently without complexity and understanding the concept behind each capabilties or what the namespace object contain that we could make use of to provide better user experience. also to know how to implement queues to dilver message on it's order without erros.
