# docker-wordpress-nginx
dockerized way to install wordpress using nginx as webserver

## install
clone this repo directly to your tools directory

rename .env.template to .env and change variables within .env

change docker-compose.yml service names marked with "XXX_CHANGEME_XXX" to uniquely identify service (e.g.: for a website about birds you might change it to "bird")

```
$ docker compose up -d
```

See https://www.reddit.com/r/nginxproxymanager/comments/vmu28y/http_proxy_does_not_work_https_does/

wordpress is ready!
