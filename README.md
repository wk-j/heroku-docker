## Heroku

```bash
docker-compose build
docker-compose up

heroku login
heroku git:remote -a dotnet-web
git push heroku master
```