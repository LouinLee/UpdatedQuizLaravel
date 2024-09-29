Cara akses project dari clone GitHub

Pre-requisities :
- Download rar file containing (env, database.sqlite)

1. composer install
2. cp .env.example .env (atau langsung menggunakan file env dari rar)
3. php artisan key:generate
4. Pindahkan database.sqlite di path projectname/database/
5. Coba run dengan php artisan serve
