# PHP-FPM with Xdebug and other DEV tools
## Supported tags and respective `Dockerfile` links
* `7.1-fpm`, `7-fpm`, `latest` [(7.1/fpm/Dockerfile)](https://github.com/Shimmi/docker-php-dev/blob/master/7.1/fpm/Dockerfile)
* `7.1-fpm-phpunit5` [(7.1/fpm-phpunit5/Dockerfile)](https://github.com/Shimmi/docker-php-dev/blob/master/7.1/fpm-phpunit5/Dockerfile)
* `7.1-zts` [(7.1/zts/Dockerfile)](https://github.com/Shimmi/docker-php-dev/blob/master/7.1/zts/Dockerfile)
* `5.6-fpm`, `5-fpm` [(5.6/fpm/Dockerfile)](https://github.com/Shimmi/docker-php-dev/blob/master/5.6/fpm/Dockerfile)

[![dockeri.co](http://dockeri.co/image/shimmi/php-dev)](https://registry.hub.docker.com/shimmi/php-dev/)

[![](https://images.microbadger.com/badges/image/shimmi/php-dev.svg)](https://microbadger.com/images/shimmi/php-dev "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/shimmi/php-dev.svg)](https://microbadger.com/images/shimmi/php-dev "Get your own version badge on microbadger.com")
[![GitHub issues](https://img.shields.io/github/issues/shimmi/docker-php-dev.svg "GitHub issues")](https://github.com/shimmi/docker-php-dev)
[![GitHub stars](https://img.shields.io/github/stars/shimmi/docker-php-dev.svg "GitHub stars")](https://github.com/shimmi/docker-php-dev)

Based on the [shimmi/php](https://store.docker.com/community/images/shimmi/php "shimmi/php") image.
This image adds some tools that are necessary for development with PHP.
Also suitable for CI/Build servers like [Jenkins](https://store.docker.com/community/images/shimmi/jenkins) and
ready-to-use [Jenkins with Blue Ocean and support for building jobs in Docker](https://store.docker.com/community/images/shimmi/jenkins) image.

## DEV Tools included
* [Xdebug](https://xdebug.org/)
* [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)
* [PHP Depend](https://pdepend.org/)
* [PHP Mess Detector](https://phpmd.org/)
* [Behat](http://behat.org/)
* [PHPUnit](https://phpunit.de/) (v6 for PHP 7; v5 for PHP 5.6 and `7.1-fpm-phpunit5`)
* [PHPLOC](https://github.com/sebastianbergmann/phploc)
* [phpcpd](https://github.com/sebastianbergmann/phpcpd)
* [phpDox](http://phpdox.de/)
