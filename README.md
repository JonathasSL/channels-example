# WORK IN PROGRESS - Django Channels Example 

This is a example Channels app that'll be used in an article I'm writing, to be published later in March. It's still very much a WIP; watch this space.

## Running on Heroku

[button]

Or, manual instructions:

- create app
- addons: postgres, redis
- settings: SECRET_KEY
- `git push heroku master`
- `heroku run python manage.py migrate`
- `heroku ps:scale web=1:free worker=1:free`

## Running locally

- postgres, redis (homebrew/postgres.app)
- locally w/o redis (postgres channel backend)
- migrate
- `h local` (not runserver)
