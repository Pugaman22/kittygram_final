# Kittygram - social network for cats photos

## Technology stack
![Static Badge](https://img.shields.io/badge/Docker-blue)

## Installation and running
- Cloning the remote repository
  
  ```
  git@github.com:Pugaman22/kittygram_final.git
  ```
- Create .env and fill it with data from env.example
  ```
  touch .env
  ```
- Running the project
  ```
  docker compose up -d
  ```
  ```
  docker compose exec backend python manage.py migrate
  ```
  ```
  docker compose exec backend python manage.py collectstatic
  ```
  ```
  docker compose exec backend python manage.py createsuperuser
  ```
- Open a link
  ```
  http://localhost/
  ```