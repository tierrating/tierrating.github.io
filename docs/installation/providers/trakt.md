---
title: Trakt
parent: Third-party providers
layout: default
nav_order: 2
---

1. Login to your Trakt account
2. Go to settings and select "Your API Apps"
3. Create a new client
    * Name: Tierlist
    * Redirect URL: https://tierlist.example.com/auth/trakt (This should point your tierlist-ui container)
4. Update the environment variables in the docker-compose.yml
    * TRAKT_CLIENT_ID
    * TRAKT_CLIENT_SECRET
    * TRAKT_REDIRECT_URL

Only the administrator of the instance needs to do these steps.