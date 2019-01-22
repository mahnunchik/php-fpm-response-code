# php-fpm-response-code

PHP-FPM Always returns 200 response code regardless PHP errors

## How to reproduce

* `http://127.0.0.1/index.php` - error page returns 200 status code
* `http://127.0.0.1/info.php` - php info

Question on stackoverflow https://stackoverflow.com/questions/54290280/php-fpm-always-returns-200-response-code-regardless-php-errors