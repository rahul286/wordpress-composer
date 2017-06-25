## Notes

Commands...

```
composer init
composer require johnpbloch/wordpress
mysql -uroot -e "create database wpcomposer"
cd wordpress
wp config create --dbname=wpcomposer --dbuser=root
composer require “scottjs/wp-dotenv:1.*"
composer config repositories.0 composer https://wpackagist.org/
composer require wpackagist-theme/p2
composer require wpackagist-plugin/wordpress-seo
composer require --dev wpackagist-plugin/debug-bar
```
