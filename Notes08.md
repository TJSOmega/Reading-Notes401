# Notes 08


### When is Basic Authorization used vs. Bearer Authorization?
Basic Authorization is used to allow a user to access an API and get information directly. Bearer Authorization provides the user with a key that can then be used to access the API for a determined amount of time.

### What does the JSON Web Token package do?
JSON Web Token package is an NPM package that allows you to load parameters into a function and then creates a web token that can be used for authentication.

### What considerations should we make when creating and storing a SECRET?
Security should be of primary concern, doing things like encrypting Secrets.


## Vocabulary:

**Encrytpion:**  Encryption is the process of encoding information. This process converts the original representation of the information, known as plaintext, into an alternative form known as ciphertext.

**Token:** A token is a special frame that is passed from node to node around a ring network. When it gets to a node that needs to transmit data, the node changes the token into a data frame and transmits it to the recipient.

**bearer:** A specific token that can be used to gain access to an API for a determined period of time.

**secret:** Information added to an authorization request.

**JSON Web Token:** an Internet proposed standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims. The tokens are signed either using a private secret or a public/private key.

