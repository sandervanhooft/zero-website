---
title: Database
description: Database
extends: _layouts.documentation
section: content
---

# Database

Using the `app:install` Artisan command you can install the `database` component:
```bash
php <your-app-name> app:install database
```

As you might have already guessed, it is Laravel's [Eloquent](https://laravel.com/docs/eloquent) component
that works like a breeze in the Laravel Zero environment too.

Usage:

```php
use DB;

DB::table('users')->insert(
    ['email' => 'enunomaduro@gmail.com']
);

$users = DB::table('users')->get();
```

Laravel [Database Migrations](https://laravel.com/docs/migrations) and [Database Seeding](https://laravel.com/docs/seeding) features are also included.
