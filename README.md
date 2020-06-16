# docker-laravel

A simple development environment for Laravel using Docker.


## Installation

Make sure you have the docker installed on your machine and clone that repository. After that, create a src folder and place all your project files inside. Now run the command `docker-compose up -d --build` and go to: [http://localhost:8080](https://localhost:8080)

Example:

```bash
|---nginx
|---mysql
|---src
    |---app
    |---bootstrap
    ...
    ...
    ...
```

Commands you may need:

- `docker-compose run --rm composer update`
- `docker-compose run --rm npm run dev`
- `docker-compose run --rm artisan migrate`

Containers that will be available for use:

- nginx
- mysql
- php
- composer
- npm
- artisan
