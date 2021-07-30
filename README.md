## Features

- Using Abstarct Factory Pattern.
- Using Repository Pattern.
- Unit tests coverage.
- Handle all Acceptance Criteria.
- easy to install in a Docker container.

## Run without Docker

You can clone The Project without Docker from
[Repo Link](https://github.com/AhmedHdeawy/orcas-task)


## Run with Docker

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
docker-compose up
```

To Run the command which fetch users from Endpoints
RUN

```sh
docker-compose exec php  sh
```
Then 

```sh
php artisan fetch:user
```

Notes: the above command will run automatically every 8 hours


Verify the server running by navigating to your server address in
your preferred browser.

```sh
localhost:8080
```

## Run API
You Can look at Endpoint using Postman here
[Postman Api](https://documenter.getpostman.com/view/3113879/TzseJky4)


## Test
```sh
php artisan test 
```

[![N|Solid](https://i.ibb.co/gVFrnn7/orcas-test.png)](https://nodesource.com/products/nsolid)

## License

MIT
