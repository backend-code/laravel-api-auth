# Install Laravel

``` javascript

composer global require laravel/installer

```

# Clone Project

``` javascript

git clone https://github.com/backend-code/laravel-api-auth.git

```

# Update Project

``` javascript

composer install

```

# Install Auth Key

``` javascript

php artisan passport:install

```

# Create Database 

``` javascript

php artisan migrate

```

# Run Serve

``` javascript

php artisan serve

```

# Setting Database

``` javascript
file: .env

DB_CONNECTION=mysql  <-- database
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=test  <-- database name
DB_USERNAME=root  <-- user name
DB_PASSWORD=  <---password

```

# Check Key

``` javascript

 php artisan key:generate

```
