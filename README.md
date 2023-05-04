# The main repository of VK RSS Bot project

![This is a project screenshot, actually](https://raw.githubusercontent.com/vertexofvortex/vk-rss-bot/main/cover.png)

## About this project
VK RSS Bot is an automatic RSS feed parser with VK publishing features. You can add the sources which you're going to parse posts from, then connect your VK page via access token and add groups from this page. Every group may have specific sources you've selected and the feed with publications from that source. Choose any post you like and then publish it to your VK group! Face the power of automation!


## Startup
```shell
docker-compose build
docker-compose up -d
```

This repo has two git-submodules, for frontend and backend. You can start them manually on your machine, but this repo contains docker-compose file that allows you to start this project as one solid service in two commands.