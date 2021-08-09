### How to run project
```
cp .env.docker .env

./develop up -d --build
./develop exec app composer install
./develop exec app php artisan migrate
```
