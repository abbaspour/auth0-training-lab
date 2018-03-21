# Auth0 Training Lab

This book is an step by step hands-on guide to Auth0 platform. 

What's this?
-----------
Auth0 is a feature reach platform and there are plenty of quality material available online.

It's great to have all the features well documented. 
 
Being a training lab booklet, this course if a little bit different and 
follow an incremental approach to build the skills gradually without being lost in all those features.          
 

Audience
--------

- Customer course
- Partner training
- Internal on-boarding 

Structure
---------
This course is split into introduction and advanced sections.

- [Setup](./setup/README.md)
    - [Auth0](./setup/auth0.md)
    - [Your machine](./setup/machine.md)

- [Intro](./intro/README.md)
    - [SPA quickstart (implicit flow / Lock)](./intro/spa.md)
    - [Regular Web quickstart (code flow + auth0.js)](./intro/regular.md)
    - different types of token and how to validate them (tokens from step 1 and 2, jwt.io)
    - Browser traffic inspector and HAR files
    - Social login
    - Scopes and consent page
    - Debugger Extension to test various flows in the debugger (e.g. PKCE and RO grant, etc)
    - Logs
    - Rules (e.g. to customise scopes and add metadata)

- advanced
    - HLP and Embedded login pages
    - SAML
        - SP
        - IdP
        - Between two tenants or between auth0 and aws
    - Custom DB (e.g. migration between tenants)
    - Delegation 
    - MFA (with OTP)
    - Passwordless (email)
    - Management API (e.g. create 3rd Party clients & search users)
    - Profiles and account linking
    - Authorization (with scopes)
    - SSO (prompt=none flow or new SSO flow, silent login, checkSession and refresh) 
    - LDAP connector (to a custom LDAP server)
    - CI/CD integration (auth0-deploy-cli)
    - Useful Extensions
        - admin delegation
        - central logging
        - wt debugger
        - github-deployment

