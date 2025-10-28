---
title: Docker
parent: Installation
layout: default
nav_order: 1
---

1. Create directory and get configuration file
```shell
mkdir tierrating
cd tierrating
wget https://github.com/RatzzFatzz/tierrating-ui/blob/main/docker-compose.yml
```
2. Configure the services you want to use 
   * [AniList](https://docs.tierrating.de/docs/installation/providers/anilist)
4. Run the application
```shell
docker compose up -d
```
4. Access the application at http://localhost:3000 or your configured domain name