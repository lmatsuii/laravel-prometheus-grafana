## create laravel app
```
docker run -v $(pwd):/var/www -w /var/www -u $(id -u):$(id -g) composer composer create-project laravel/laravel serviceA
```