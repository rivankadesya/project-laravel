cara download

git clone git@github.com:rivankadesya/project-laravel.git
cd laravel-8-complete-blog
cp .env.example .env
composer install
php artisan key:generate
php artisan cache:clear && php artisan config:clear
php artisan serve


sebelum mulai buat database bernama
metaco (hanya database saja)


seting .env 


DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=metaco
DB_USERNAME={USERNAME}
DB_PASSWORD={PASSWORD}