# Intro to JWT

_1. What is a JSON Web Token (JWT)?_

  Json Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. 


_2. When should we use JSON Web Tokens?_

  Authorization: This isthe most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token.
  
  Information Exchange: JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed - by using public/private key pairs, for example - you can be sure the senders are who they say they are. Additionally, as the signature is calculated using the header and the payload, you can also verify that the content hasn't been tampered with.


_3. Claims are expected in which structural component of a JWT?_

  Claims are expected during the payload component of a JWT.
  

# Are JWTs Secure?

_1. If I get a JWT and I can decode the payload, how can we call that secure?_

  JWTs can be either signed, encrypted or both. If a token is signed, but not encrypted, everyone can read its contents. But when you don't know the private key, you can not change it. Otherwise, the receiver will notice that the signature won't match anymore. 
  

_2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature._

  When sending a JWT, the sender and receiver must know the private key that goes with the payload. Without this, someone can alter the payload but will not be able to recreate the matching signature and will be rejected by the receiver.


_3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter._

  When sending content, the sender and a receiver share a secret that is separate from the content being sent. When the sender sends the content, the receiver will not accept it unless it is paired with the correct secret that only the sender and the receiver know to create the correct signature. Without this correct secret, the receiver will reject the content.
  

# JWTs Explained

_1. Why use JWT?_

   To securely transfer information between two bodies - JWTs are digitally signed which means their information can be verified and trusted.
  

_2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend._

  Because it is compact, it can be sent via means such as URL, POST request, HTTP Header, etc. for extremely fast transmission.
  
  Being self-contained allows the user to avoid querying the database multiple times.


_3. What are the three components (the structure) of a JWT signature?_

  Header, Payload, and Signature. 
