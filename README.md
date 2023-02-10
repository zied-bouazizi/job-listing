# job-listing

An application for job listing with Laravel 9 and MySQL

## Usage

### Install Dependency
```
composer install
```

### Database Setup
Setup a database and then add your db credentials (database, username and password) to `.env`

### Migrations
To create all the nessesary tables and columns, run the following
```
php artisan migrate
```

### Seeding The Database
To add dummy data, run the following
```
php artisan db:seed
```

### File Uploading
When uploading files, they go to "storage/app/public". Create a symlink with the following command to make them publicly accessible
```
php artisan storage:link
```

### Running Then App
```
php artisan serve
```
