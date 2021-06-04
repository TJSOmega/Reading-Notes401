# Notes 07

### Access Order:

*(Not sure how correct this is?)*

1. Register your application to get a client_id and client_secret

2. Ask the client if they want to sign in via a third party

3. Redirect to a third party authentication endpoint

4. Receive authorization code

5. Make a request to the access token endpoint

6. Receive access token

7. Make a request to a third-party API endpoint



### What can you do with an authorization code?:
 make a request to get an access token.


### What can you do with an access token?:
The access code is used for authentication.

### What’s a benefit of using OAuth instead of your own basic authentication?:
Keeps users information secure by not sharing them over the internet multiple times.



### Vocabulary

**Client ID:** The client_id is a public identifier for apps. Even though it’s public, it’s best that it isn’t guessable by third parties, so many implementations use something like a 32-character hex string. It must also be unique across all clients that the authorization server handles. If the client ID is guessable, it makes it slightly easier to craft phishing attacks against arbitrary applications.

**Client Secret:** The client_secret is a secret known only to the application and the authorization server. It must be sufficiently random to not be guessable, which means you should avoid using common UUID libraries which often take into account the timestamp or MAC address of the server generating it. A great way to generate a secure secret is to use a cryptographically-secure library to generate a 256-bit value and converting it to a hexadecimal representation.


**Authentication Endpoint:**
Endpoint used to authenticate a user.


**Access Token Endpoint:**
Enpoint used for issuing access tokens to clients.

**API Endpoint:**
 Point of entry in a communication channel when two systems are interacting.

**Authorization Code:**
 Temporary code that the client will exchange for an access token.

**Access Token:**
Object encapsulating the security identity of a process or thread.