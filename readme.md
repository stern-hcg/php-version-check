###使用方法



```
1. git clone 

2. composer install 

3. ./vendor/bin/phpcs --config-set installed_paths vendor/phpcompatibility/php-compatibility

4. usage example

-  using PHPCompatibility to check current directioy project 
./vendor/bin/phpcs -p . --standard=PHPCompatibility

-  using PHPCompatibility and PHPCompatibilitySymfonyPolyfillPHP72  to check current directioy project 
./vendor/bin/phpcs -p . --standard=PHPCompatibility,PHPCompatibilitySymfonyPolyfillPHP72 

-  using PHPCompatibility to check target project 7.0-7.2 compatibility and report to check_report.log
./vendor/bin/phpcs --standard=PHPCompatibility --runtime-set testVersion 7.0-7.2  /Users/Admin/Documents/projects/trade_center >> ./check_report.log


```