---
title: AniList
parent: Third-party providers
layout: default
nav_order: 1
---

1. Login to your AniList account
2. Go to settings > Developer
3. Create a new client
    * Name: Tierlist
    * Redirect URL: https://tierlist.example.com/auth/anilist (This should point your tierlist-ui container)
4. Update the environment variables in the docker-compose.yml
    * ANILIST_CLIENT_ID
    * ANILIST_CLIENT_SECRET
    * ANILIST_REDIRECT_URL

Only the administrator of the instance needs to do these steps. 
