# API Integration

## Review API Server Build

Explain the different between a query string parameter and a path parameter.

>The difference is that query params represents actually a question if would say or from it's name a query, so we put a questionmark after the type of the query we are building our request on, then passing the argument or the content of our query as a parameter to usually build our server request on after that questions mark, it's like a conditional , `products?category=electronics` which means `what is the value of products, if the category was electronics` so the result of products depends on this query passed after, also in the request itself the queries are saved under the obj of query. queries are optional usually to access a certain content

>On the otherhand,path params could be passed in whichever position the developer define for that website url, and it's harder to mainpulate and combine. they are saved in params object inside the request and the value is passed directly from the url , whichever word takes place of the param it will be the value of that param.

What would our API URL with a path id parameter be given the following information:
Domain: http://our-site.com
v3
model name: stuff
id: things

>Path parameter URL: http://our-site.com/v3/stuff/things

We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
>Imagine a vending machine for coffee, you should pass multiple options to make up the recipe of your coffee and finally retrieve that coffee, based on the options you clicked on that vending machine the coffee end result differs, the same for an API, it's like that vending machine, you compose the url by passing data and based on the data when you click enter you send the order to our server which will translate it based on the ingredients and bring the coffee to you by mixing these ingredients together after getting these ingredients from the Database, each user will have different information result(different coffee) based on the options that was entered.

## Review Auth Server Build

Describe how you would use middleware to implement basic and bearer auth.

>For basic auth it quite simple, just by making user models in my database which requires a username and password to create, then I would link each route with a middle ware that checks if the current user is found in the database with a matching password, so whenever a user hit a route this process will keep happening, but with bearer auth it will become easier since I will just save the bearer token inside a cookie, and whenever the user hits that bearer protected route, it will check if the token is valid for such user so he can access these information.

Describe the handshake necessary to implement OAuth.
>A hand shake is as it tells, like an agreement, using OAuth, is like trusting a certain third party, to authenticate a certain user to access resources on a different platform, like when you login to twitter using your google account, if you successfully logged in inside google, this will ask you to grant permission for the site you want to access such as twitter to read your data, then you will grant a temporary token that allows you to access protected data of that website.

Describe how Role Based Access Control works to a non-technical friend.

>if you have ever played RPG online games, there will be like GM , Moderators , Players for example.
the players can do regular tasks in the game and missions and they should follow the hardest way to get them done also they have no control over some events, while the Moderators could initiate an event in the game and teleport quickly to another place with just 1 second, while the GM who is the highest role order, he can delete everyone one who goes below him, he can ban any player account / Moderator account and he can kill all the game players with 1 hit.

## Things I want to know more about

Implementing Auths in the front-end.
