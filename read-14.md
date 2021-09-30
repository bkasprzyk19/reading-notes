[<==Back](README.md)

Reading

What is OAuth


What is OAuth?

"OAuth definition
OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization."

Give an example of what using OAuth would look like.

How does OAuth work? What are the steps that it takes to authenticate the user?

"OAuth examples
The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website."

What is OpenID?

"Well, OpenID is about authentication: as a commenter on StackOverflow pithily put it: "OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans.""

Authorization and Authentication flows

What is the difference between authorization and authentication?

Content from":
https://auth0.com/docs/authorization/flows

What is Authorization Code Flow?

"Because regular web apps are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow, which exchanges an Authorization Code for a token."

https://auth0.com/docs/authorization/flows/authorization-code-flow

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

"During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security. Additionally, single-page apps have special challenges. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE)."

https://auth0.com/docs/authorization/flows/authorization-code-flow-with-proof-key-for-code-exchange-pkce

What is Implicit Flow with Form Post?

"As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets. While this is no longer considered a best practice for requesting Access Tokens, when used with Form Post response mode, it does offer a streamlined workflow if the application needs only an ID token to perform user authentication."

https://auth0.com/docs/authorization/flows/implicit-flow-with-form-post

What is Client Credentials Flow?

"With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow (defined in OAuth 2.0 RFC 6749, section 4.4)."

https://auth0.com/docs/authorization/flows/client-credentials-flow

What is Device Authorization Flow?

"With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text. To do this, device apps use the Device Authorization Flow (drafted in OAuth 2.0). For use with mobile/native applications."

What is Resource Owner Password Flow?

https://auth0.com/docs/authorization/flows/resource-owner-password-flow