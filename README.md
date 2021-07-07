
Authentication is a complex and exciting topic that involves using many of the concepts we've already studied as well as several new ideas. 

An authentication system allows the registration / signup of new users and allows those users to sign in. It has to be able to identify each user and keep their information private and secure.

Being able to develop secure user login systems is in fact a whole career and life path in and of itself, but understanding the broad concepts of **Auth** is critically import for all developers. 

Describing auth flow and understanding key terms are very common **interview questions** for junior developers, so lets take some time to research and understand auth and the related concepts.

## Setup

Fork and clone this repository and answer the questions as you research directly in the README. You do not have to pull request and submit this lab, but you will want to have it on hand for reference in the future. 

## Auth Concepts Worksheet

#### Define the following

1. *Authentication*
The act of proving an assertion. Authentication is the process of verifying identity. 

2. *Authorization*
The action or fact of authorizing or being authorized.

3. Explain how *authentication* and *authorization* are related but distinct concepts.
Authentication is the act of proving you are a specific user, authorization is the process of being granted access. 

5. *Sessions vs Token based auth*
Session based authentication is stored on the server. 
Token based authentication is one in which the user state is stored on the client.

6. *json web token (also know as a jwt)*
JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.

7. *Encoding, encryption and hashing* along with the uses for and differences between the three
-Encoding: Reversible transformation of data format, used to preserve usability of data.
-Hashing: Is a one-way summary of data, cannot be reversed, used to validate the integrity of data.
-Encryption: Secure encoding of data used to protect confidentiality of data.

8. *oAuth* (pronounced oh-Auth)
OAuth is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password. Such as when you use your Google account to authorize other 3rd party vendors. 

#### Explore and then describe the following npm packages:

1. [bcrypt](https://www.npmjs.com/package/bcrypt)
A password hashing program - it encodes a password for transmission
2. [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
a compact and self-contained way for securely transmitting information between parties
3. [passport](https://www.npmjs.com/package/passport)
Authentication middleware for Node

    * also describe what a *strategy* is in the context of this npm package

Authentication mechanisms, known as strategies, are packaged as individual modules. Applications can choose which strategies to employ, without creating unnecessary dependencies.

---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.