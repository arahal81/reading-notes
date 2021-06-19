# reading11

## OAuth

1. What is OAuth?
    * is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.
2. Give an example of what using OAuth would look like.
    * Netlify
3. How does OAuth work? What are the steps that it takes toauthenticate the user?
    
    1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

    2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

    3. The first site gives this token and secret to the initiating user’s client software.

    4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
    5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

    6. The user approves (or their software silently approves) a particular transaction type at the first website.The user is given an approved access token (notice it’s no longer a request token).

    7. The user gives the approved access token to the first website.
    8. The first website gives the access token to the second website as proof of authentication on behalf of the user.

    9. second website lets the first website access their site on behalf of the user.

    10. The user sees a successfully completed transaction occurring.
4. What is OpenID?
    * OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?
    * Authentication confirms that users are who they say they are.
    * Authorization gives those users permission to access a resource.
2. What is Authorization Code Flow?
    * Authentication is the act of validating that users are whom they claim to be. This is the first step in any security process. Giving someone
      permission to download a particular file on a server or providing individual users with administrative access to an application are good examples of authentication
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
    * The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users.
4. What is Implicit Flow with Form Post?
    * It is intended for Public Clients, or applications which are unable to securely store Client Secrets.
5. What is Client Credentials Flow?
    * If the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + 
      password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow, in which they pass along their Client ID and Client Secret to authenticate themselves and get a token.
6. What is Device Authorization Flow?
    * It is where the device asks the user to go to a link on their computer or smartphone and authorize the device.
