# craft-codespace

getting started

```
cp .env.example .env

docker-compose run --rm composer composer install

docker-compose run --rm console php craft install/craft --email admin@craftcms.com --language en-GB --password password --site-name "Codespace demo" --site-url @siteUrl

docker-compose up -d craft console
```