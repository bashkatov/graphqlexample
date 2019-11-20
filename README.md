# GraphQL tutorial

Thanks Christopher Moore for a [great tutorial](https://www.toptal.com/graphql/laravel-graphql-server-tutorial)!

ATTENTION: The newer versions of graphQL have different arguments for pagination query (first, page). Where first is the number of records per page, and page is the offset from which records are to be returned, so some examples from [linked article](https://www.toptal.com/graphql/laravel-graphql-server-tutorial) will not work. You need to correct them!

Create new laravel project:
```bash
$ laravel new tutorial
```

Edit ```.env``` file:
```bash
DB_CONNECTION=sqlite
# DB_HOST=
# DB_PORT=
# DB_DATABASE=database.sqlite
# DB_USERNAME=
# DB_PASSWORD=
```

Create database file:
```bash
$ touch ./database/database.sqlite
```

Migrate and seed:
```bash
$ php artisan migrate
$ php artisan db:seed
```

That's all.
