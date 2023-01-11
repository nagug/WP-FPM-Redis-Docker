## Wordpress-PHP-FPM with redis, memcache, tidy

This is derived from official wordpress-php-fpm image.

Added support for the following
1. Redis
2. Memcache
3. Tidy

Versions: 
- Imagick version: 3.7.0
- Redis version: 5.3.7
- Php-fpm: 8.2
- wordpress base version: 6.1.1


Might need to update the php.ini file to enable these. Memcached might get a server error depends.(so not recommended). Also update the nginx vhost file appropriately
