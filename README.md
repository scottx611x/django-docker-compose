# django-docker-compose
Demo of how one can utilize docker-compose to run a basic Django app

## Why `docker-compose`?:
- Ease of setup:
  - Everything that is needed to setup a multi-container application with Compose is a single file configuration file
  - Your entire development enviornment can be started with one command
- Ease of collaboration:
  - No need to have complicated installation instructions
  - Exact copies of local environments (No more version creep)

## Pre-Reqs:
- docker

## Running:
- `git clone https://github.com/scottx611x/django-docker-compose.git && cd django-docker-compose`
- `docker-compose up`
- Go to: http://localhost:8000
- 🎉🎊🎊🎉

## Tests:
- `docker-compose run app python3 manage.py test`

## Shutting down:
- `Ctrl + C` or `docker-compose down`
