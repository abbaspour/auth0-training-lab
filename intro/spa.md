Single Page Application
=======================

Single page web applications use what is know as 2 way dance or implicit grant OAuth flow. 
Due to their nature running in the client side, no client secret can be stored safely.
As a result, client directly receives `access_token` and `id_token` from authorization server (AS).  

Let's setup a simple Single Page Application (SPA) in Auth0.
