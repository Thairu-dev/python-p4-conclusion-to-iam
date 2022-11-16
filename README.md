# Conclusion to Identity and Access Management

## Learning Goals

- Create an application that requires users to authenticate with usernames and
  passwords.
- Retrieve data from cookies to allow users to access data from previous
  sessions.
- Authorize users to access different sets of resources based on their
  attributes.
- Establish database rules through SQLAlchemy to encrypt passwords and protect
  users' private information.

***

## Key Vocab

- **Identity and Access Management (IAM)**: a subfield of software engineering
  that focuses on users, their attributes, their login information, and the
  resources that they are allowed to access.
- **Authentication**: proving one's identity to an application in order to
  access protected information; logging in.
- **Authorization**: allowing or disallowing access to resources based on a
  user's attributes.
- **Session**: the time between a user logging in and logging out of a web
  application.
- **Cookie**: data from a web application that is stored by the browser. The
  application can retrieve this data during subsequent sessions.

***

## Conclusion

In this module, you covered many of the basic concepts in identity and access
management:

- Using cookies and sessions to remember users.
- Authentication using Flask's `session` object.
- Differentiating authentication and authorization.
- Authorizing users to access resources based on their session attributes.
- Adding passwords to authentication.
- Encrypting passwords with `Bcrypt` for added security.
- ...and doing it all in the same time in our "Putting it All Together" Lab!

IAM is a field generally populated by specialists who spend every working hour
on authentication, authorization, encryption, and more. It is also a field where
pre-made products, like those by [ForgeRock](https://www.forgerock.com/) or
[Azure Active Directory](
https://azure.microsoft.com/en-in/products/active-directory/). Your new set of
knowledge will help you to understand what's going on behind the scenes in
either.

That being said, IAM is also a _rapidly evolving_ field, with new major players
joining the scene every few months. If you enjoyed this module and feel like
digging into some _tough_ problems, you can continue researching the field and
building IAM solutions of your own.

***

## Resources

- [Introduction to Identity and Access Management (IAM) - auth0](https://auth0.com/docs/get-started/identity-fundamentals/identity-and-access-management)
- [What is Authentication? - auth0](https://auth0.com/intro-to-iam/what-is-authentication)
- [API - Flask: `class flask.session`](https://flask.palletsprojects.com/en/2.2.x/api/#flask.session)
- [What is Authorization? - auth0](https://auth0.com/intro-to-iam/what-is-authorization)
- [What are cryptographic hash functions? - Synopsys](https://www.synopsys.com/blogs/software-security/cryptographic-hash-functions/)
- [Flask-Bcrypt](https://flask-bcrypt.readthedocs.io/en/1.0.1/)
