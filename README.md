# laravel-packages-developer-cw
Basic instructions for working with the development of CW packages for laravel

In the file composer.json include the path to the synchronous repositories, this makes it easier to debug packages for development.
```php
  "repositories": [
        {
            "type": "path",
            "url": "../packages/confrariaweb/*",
            "options": {
                "symlink": true
            }
        }
    ],
```
This procedure should only be used for development, this approach is not recommended for the production environment.
