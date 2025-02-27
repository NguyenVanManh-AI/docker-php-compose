### Build Docker Container 
- `docker compose up --build -d`

### Check php, composer version  
- `docker exec -it php_app bash`
- `php -v`
- `composer -v`
- `php index.php`

### Run laravel 
- (new project) : `composer create-project --prefer-dist laravel/laravel:^10.0 laravel10`
- `cd laravel10` 
- copy .env.example -> .env 
- (run project) : `php artisan serve --host=0.0.0.0 --port=8000`
- http://localhost:8000/

### Check connect db 
- `php artisan optimize:clear`
- `php artisan optimize`
- `php artisan migrate` 

### Connect MySQL GUI
- hostname: `127.0.0.1`
- username: `laravel_user`
- password: `laravel_password`
- port: `3309` 
