## Heroku

```bash
docker-compose build
docker-compose up

heroku login
heroku stack:set container
heroku git:remote -a dotnet-web
git push heroku master
```