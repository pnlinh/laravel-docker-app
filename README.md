### How to run project
```
cp .env.docker .env

./develop up -d
./develop exec app composer install
./develop exec app php artisan migrate
```
