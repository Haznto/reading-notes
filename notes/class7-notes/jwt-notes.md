# Bearer Authorization

## Intro to JWT

- What is a JSON Web Token (JWT)?

>A JSON Web Token (JWT) is a compact, URL-safe means of representing claims between two parties. It is a self-contained token that contains information in a structured manner. JWTs consist of a header, a payload, and a signature.

- When should we use JSON Web Tokens?

>simply to generate tokens that would make it easier for the user to have a longer authorized sessions using his application.

- Claims are expected in which structural component of a JWT?

>Claims are expected in the payload component of a JWT.

---
## Are JWTs Secure?

- If I get a JWT and I can decode the payload, how can we call that secure?

>Decoding is a normal process to be done and it's not theo nly factor affects security in jwt , mainly it's based on the integrity of the signiture jwt use.

- If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

>the shared secret or key that is used to generate and verify the signature

- Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

> the content is like a box of gifts, that is hidden inside a box with a lock, to get the gifts, which represents the valuable information for the user, you must own the key of that box, then you can start unrapping (decoding) your gifts.
---
## JWTs Explained

- Why use JWT?
> Stateless Nature: JWTs act as self-contained tokens, eliminating the need for the server to store session information for each user. This characteristic reduces server-side storage requirements and enhances scalability.

>Enhanced Security: JWTs employ digital signatures, guaranteeing the integrity of data within the token. Additionally, JWTs can be encrypted to safeguard sensitive information from unauthorized access.

>Cross-Domain Communication: JWTs facilitate secure communication by enabling the transmission of information between different domains or systems in a reliable and protected manner.

>Flexibility: JWTs offer versatility by supporting custom claims, empowering developers to include additional relevant data within the token. This flexibility enhances the capability to tailor JWTs to specific application requirements.

>By leveraging these advantages, JWTs provide an effective solution for managing authentication, authorization, and secure data exchange in a variety of scenarios.

- JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

>it's like a smart id card that contains all of your data, and you can use it to access all things needed by you.

- What are the three components (the structure) of a JWT signature?

>Header ,Payload ,Signature

---
## Things I want to know more about

>how to encrpt and secure the token in a manual way, and want to know about other techonologies that deals with tokens.
