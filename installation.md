---
title: Installation
layout: home
---

1. Create directory and get configuration file
```shell
mkdir tierrating
cd tierrating
wget https://github.com/RatzzFatzz/tierrating-ui/blob/main/docker-compose.yml
```
2. Create an application in the anilist developer settings (For the time being this is necessary, because otherwise I have to provide a centralized authentication server)
3. Update the env variables within in the compose file
4. Run the application
```shell
docker compose up -d
```
5. Access the application at http://localhost:3000 or your configured domain name