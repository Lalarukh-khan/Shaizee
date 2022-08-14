# shaizee

git clone https://github.com/Lalarukh-khan/shaizee.git shaizee

cd shaizee

composer install

# write cp if using linux AND copy if using windows

copy .env.expample .env

php artisan key:generate

# set up database and email
php artisan migrate

php artisan storage:link

npm install && npm run dev

php artisan serve

# To make changes on site and see results

npm run watch

Again run this command: npm run dev

Run this on another CMD: php artisan serve
