# cara-install-laravel

# cara install :

download dan ekstrak project di local server anda contoh di C:\xampp\htdocs\folder-aplikasi

Buat nama database di server localhost/phpmyadmin anda dengan nama : folder-aplikasi

rename file .env.example to .env dan sesuaikan : DB_DATABASE=folder-aplikasi

buka terminal dan arahkan ke folder project contoh : cd C:\xampp\htdocs\folder-aplikasi

jalankan perintah :

composer update

php artisan key:generate

php artisan storage:link

php artisan migrate

php artisan db:seed

php artisan serve

buka browser dan jalankan http://localhost:8000
done ................................................................
