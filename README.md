# Laravel Docker Starter Kit

Suitable for starting Laravel projects with Docker.

## How To Deploy

### For first time only !

- `git clone https://github.com/Gobozzz/laravel-starter.git`
- `cd laravel-docker`
- `docker compose up -d --build`
- `docker compose exec php bash`
- `composer setup`

### From the second time onwards

`docker compose up -d`

### env.example -> .env

`cp .env.example .env`

### Laravel App
- URL: http://localhost
