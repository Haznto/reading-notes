# Authentication

***Authentication** is an important topic because each website that has huge economical sides, has user who use it, such as facebook, twitter, etc.. and those are website serving users and their data, to protect these data and such privacy, and to make the users feel safe using these website, authentication is a must, so it can ensure that each user has only access on his/her sensitive information.*

## **Securing Passwords**

 **1- Explain to a non-technical friend how you would safely hash and store a password.**

*Simply by passing the password to a software, which will perform a certain process called (bycrypt function) that will make calculations to produce an equivalent value but in a different secret language only that software knows, then we store it as is.*

 **2- What is Bcrypt?**

 >Bcrypt is an adaptive hashing function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.

 **3- Why might you use something like Bcrypt?**

 *Because it has much benefits such as providing the complexity factor and even has the stretching feature, makes it harder as hell to break a password.*

## **Basic Auth****

**1- What is Basic Authentication?**

*It is a method related to http request that helps providing a username and a password while making that request.*

**2- What properties are necessary in the header of a Basic Auth request?**

- *The Authentication header that includes the credentials joined by a colon.*

- *The header has to be cached first by the web browser for a period of time.*

**3- How are username:password in Basic Auth encoded?**

*It's encoded in Base64 as ID and password joined by a colon.*

## **OWASP auth cheatsheet**

**1- Define the authentication process to a non-technical recruiter.**

It's like a verification process, in real life for example, when you go in the airport and they ask you for the tickets and the passport to make sure you are booked and allowed to enter the plane, the same thing happens on IT world, you have to provide data that ensures you are the person who you claim to be.

**2- How should your error messaging respond (both HTTP and HTML)? Why?**

*In a generic manner regardless of the account state, so it will make it more secure for those who are trying to break to some accounts and give them zero information about the account status. and HTTP method erros should match the generic message too, not making a conflict and exposing the account status by sending a 200 code for exisitng account and 401 for example.*

## **Things I want to know more about.**

*I want to learn more about hashing technologies and about the cyber-security side of protecting our websites.*