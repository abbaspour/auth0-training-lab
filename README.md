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
    - [SPA quick-start (implicit flow)](./intro/spa.md)
    - [Regular Web quick-start (code flow)](./intro/regular.md)
    - [Auth0 Authentication API](intro/authentication-api.md)
    - [JWT](./intro/jwt.md)
    - [Browser Inspector](./intro/inspector.md)
    - [Social Login](./intro/social.md)
    - [Hosted Login Page](./intro/hlp.md) 
    - [Rules](./intro/rules.md)
    - [Forgotten Password Flow](./intro/forgotten-password.md)
    - [Auth0 Management API](./intro/management-api.md)
- [Advanced](./advanced/README.md)
    - HLP and Embedded login pages
    - SAML
        - SP
        - IdP
        - Between two tenants or between auth0 and aws
    - Custom DB (e.g. migration between tenants)
    - Scopes and consent page
    - MFA (with OTP)
    - Passwordless (email)
    - Management API (e.g. create 3rd Party clients & search users)
    - Debugger Extension to test advanced flows in the debugger (e.g. PKCE and RO grant, etc)
    - [Profiles and Account Linking](./advanced/profile.md)
    - Authorization (with scopes)
    - SSO (prompt=none flow or new SSO flow, silent login, checkSession and refresh)
    - Cross Origin 
    - LDAP connector (to a custom LDAP server)
    - CI/CD integration (auth0-deploy-cli)
    - Useful Extensions
        - admin delegation
        - central logging
        - wt debugger
        - github-deployment

