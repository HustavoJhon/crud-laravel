# PHP & MYSQL & PHPMYADMIN & DOCKER

[![Laravel](https://img.shields.io/badge/3.11.2-black?style=flat&logo=laravel)](https://github.com/hustavoJhon/basic/)

```bash
sail php artisan migrate
sail php artisan make:model Empleado -mcr
sail php artisan route:list
```


```bash
alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'
```

```php
sail up
sail up -d
sail stop
```

**Exectuting commands**
```php
# Running Artisan commands locally...
php artisan queue:work
 
# Running Artisan commands within Laravel Sail...
sail artisan queue:work
```

**Execution PHP Commands**

sail php --version
 
sail php script.php

**Executing Composer Commands**

sail composer require laravel/sanctum

**Executing Artisan Commands**

sail artisan queue:work

**Executing Node/NPM Commands**

sail node --version
sail npm run dev
