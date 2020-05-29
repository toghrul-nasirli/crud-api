# CRUD API

Laravel 7 API that uses the API resources. This is an API for simple CRUD app

## Installation

```bash
# Installing Dependencies
composer install

# Create a database and edit the ".env" file as your desired

# Running Migrations
php artisan migrate

# Importing Posts From Seeder
php artisan db:seed

# If APP_KEY is empty, you have to generate an encryption key
php artisan key:generate
```

## Routes

### List all posts
```
GET api/posts
```

### Get single post
```
GET api/post/{id}
```

### Add post
```
POST api/post
title, body
```

### Update post
```
PUT api/post
post_id, title, body
```

### Delete post
```
DELETE api/post/{id}
```
