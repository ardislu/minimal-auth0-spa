# minimal-auth0-spa

The minimum code required to integrate an Auth0 login using vanilla JavaScript with no dependencies.

Implemented functions:
- Login using [Authorization Code Flow with PKCE](https://auth0.com/docs/get-started/authentication-and-authorization-flow/add-login-using-the-authorization-code-flow-with-pkce)
- Login using Implicit Flow with id_token in URL fragment (**deprecated**): this flow should only be used if `Authorization Code Flow with PKCE` can't be used. There's no direct how-to article but [this article](https://auth0.com/docs/get-started/authentication-and-authorization-flow/implicit-flow-with-form-post) is close.
- Logout 
