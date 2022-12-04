# Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password.

    Passwords are stored using a hashing algorithm. Cryptographic hash algorithms MD5, SHA1, SHA512, and SHA-3 are general purpose hash functions, designed to calculate a digest of huge amounts of data in as short a time as possible. Hashing is the greatest way for protecting passwords and considered to be safe for ensuring the integrity of data or passwords.

2. What is Bcrypt?

    BCrypt is an adapting hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor) which allows you to determine how expansive the hash function will be.
    
    This work factor value determiens how slow the hash function will be, meaning different work factors will generate different hash values in different time spans, which makes it extremely resistant to brute force attacks.

3. Why might you use something like Bcrypt?

    BCrypt would be used to slow down brute force cyber attacks using a technique called Key Stretching.
    

# Basic Auth

1. What is Basic Authentication?

    In the context of an HTTP transaction, basic access authentication is a method for an HTTP user agent (eg. a web browser) to provide a username and password when making a request. In basic HTTP authentication, a request contains a header field in the form of Authorization: Basic <credentials>, where credentials is the Base64 encoding of ID and password joined by a single colon.

2. What properties are necessary in the header of a Basic Auth request?

    The BA field has to be sent in the header o each HTTP request.
  
    When the server wants the user agent to authenticate itself towards the server after receiving an unauthenticated request, it must send a response with a HTTP 401 Unauthorized status line and a WWW-Authenticate header field.
  
    When the user agent wants to send authentication credentials to the server, it may use the Authorization header field.

3. How are username:password in Basic Auth encoded?
  
    They are encoded with Base64 in transit and not encrypted aor hashed in any way.
  
# OWASP Auth Cheat Sheet
  
1. Define the authentication process to a non-technical recruiter.

    Authentication is the process of verifying that an individual, entity, or website is whom it claims to be. Authentication in the context of web applications is commonly performed by submitting a username or ID and one or more items of private information that only a given user should know.
  
2. How should your error messaging respond (both HTTP and HTML)? Why?

    An application should respond (both HTTP and HTML) in a generic manner in order to prevent the creation of a discrepancy factor that could allow an attacker to mount a user enumeration action against the application.
