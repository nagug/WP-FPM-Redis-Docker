## Wordpress-PHP-FPM with redis, memcache, tidy

This is derived from official wordpress-php-fpm image.

Added support for the following
1. Redis
2. Memcache
3. Tidy

Might need to update the php.ini file to enable these. Memcached might get a server error depends.(so not recommended). Also update the nginx vhost file appropriately
