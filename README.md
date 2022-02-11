# Project
## Setup
```
#Clone the repository
git clone

#Install dependencies
composer install

#Copy the environment file
cp .env.example .env

#Run the key generator
php artisan key:generate

#Publish the storage link
php artisan storage:link

#Start server
php artisan serve
```

Access the application at: [http://127.0.0.1:8000/city/miami](http://127.0.0.1:8000/city/miami)

## Features
### Add new city
1. Copy the city data file with name `[NAME_CITY]-page-data.json` to the `/storage/app/public` directory.
2. Run `php artisan serve` to restart the server.
