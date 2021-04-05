Media manager for laravel-admin
===============================

Media manager for `local` disk.

具体请参考

[Documentation](http://laravel-admin.org/docs/#/en/extension-media-manager) | [中文文档](http://laravel-admin.org/docs/#/zh/extension-media-manager)

## Installation

```shell
// For laravel-admin 1.x
composer require rdios/media-manager:1.x -vvv

// For laravel-admin 2.x
composer require laravel-admin-ext/media-manager:2.x -vvv

php artisan admin:import media-manager
```

Add a disk config in `config/admin.php`:

```php

    'extensions' => [

        'media-manager' => [
        
            // Select a local disk that you configured in `config/filesystem.php`
            'disk' => 'public'
        ],
    ],

```


Open `http://localhost/admin/media`.

License
------------
Licensed under [The MIT License (MIT)](LICENSE).
