# Project_Y2
 
run these commands when clone Project

composer install
mv .env.example .env
php artisan cache:clear
composer dump-autoload
php artisan key:generate

.env setting
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=practicedb
DB_USERNAME=root
DB_PASSWORD=

SESSION_DRIVER=file
SESSION_LIFETIME=120
SESSION_ENCRYPT=false
SESSION_PATH=/
SESSION_DOMAIN=null

https://github.com/Thanipha?tab=repositories
