# Auth0 Training Lab


Structure
---------

- 00-setup
    - auth0 setup
    - machine setup

- 01-intro
    - SPA quickstart (implicit flow / Lock)
    - Regular Web quickstart (code flow + auth0.js)
    - different types of token and how to validate them (tokens from step 1 and 2, jwt.io)
    - Browser traffic inspector and HAR files
    - Social login
    - Scopes and consent page
    - Debugger Extension to test various flows in the debugger (e.g. PKCE and RO grant, etc)
    - Logs
    - Rules (e.g. to customise scopes and add metadata)

- 02-advanced
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

