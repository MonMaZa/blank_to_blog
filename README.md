# blank_to_blog
Pest, Jetstream, Laravel

# # Installation

composer install (It can run all necessary dependencies)

For my memory to create a new laravel blog

(1)
composer create-project laravel/laravel:^10.0 example-app 
[for pest->  composer require --dev pestphp/pest]
vendor/bin/pest --init

OR
laravel new example-app --pest

(2)
php artisan test

(3)
composer require laravel/jetstream
php artisan jetstream:install inertia --pest

(4)
php artisan test

(5) Run
php artisan serve

=================
# Artisan Commands

php artisan make:model
factory, migration, policy, resource

php artisan migrate:fresh --seed

php artisan route:list
