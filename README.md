# laravel-itesm-april-2017-session-1

1) After downloading this repository run:

```
composer install
```

2) Create your .env file with a content like this:

```
APP_NAME=Laravel
APP_ENV=local
APP_KEY=base64:K1XlySWHfg7UPOtaNDDH1joMNI6hQKBAQlBO1fx6jNI=
APP_DEBUG=true
APP_LOG_LEVEL=debug
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_blog
DB_USERNAME=laravel_blog_user
DB_PASSWORD=JxzBC32YcAYsP3Ns

BROADCAST_DRIVER=log
CACHE_DRIVER=file
SESSION_DRIVER=file
QUEUE_DRIVER=sync

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_DRIVER=smtp
MAIL_HOST=smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
```

3) Double-check the database connection params:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_blog
DB_USERNAME=laravel_blog_user
DB_PASSWORD=JxzBC32YcAYsP3Ns
```