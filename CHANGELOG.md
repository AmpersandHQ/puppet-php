## 0.3.6 ##

* Fix file permissions when installing PHP
* Fix file permissions on versions installed prior to this fix
* Configure PEAR cache and download folders fixing most PEAR errors

## 0.3.5 ##

* Add `pkgconfig` as a dependency - required for some extensions

## 0.3.4 ##

* Fix dependency error causing installation to fail

## 0.3.3 ##

* Minor bug fixes to improve reliability of installation

## 0.3.2 ##

* Add git extension provider - install PHP extensions from a git repository
* Add zeromq extension

## 0.3.1 ##

* Minor bug fixes

## 0.3.0 ##

* Add custom provider to install PHP extensions from PECL
* Add remaining versions of PHP to be installed
* Add APC, HTTP, Memcached & Zookeeper extension classes
* Add example nginx config template - this (or similar) should be used for PHP based projects

## 0.2.0 ##

* Complete rebuild of PHP installation method, making the process _significantly_ more reliable
* Remove php-build and replace with custom Puppet provider
* Fix issues with different autoconf requirements for PHP 5.3 and 5.4

## 0.1.2 ##

* Fix incorrect php.ini load path
* Minor bug fixes

## 0.1.1 ##

* Bug fixes
* Fix missing dependencies
* Fix nginx fastcgi params

## 0.1.0 ##

* Add PHP-FPM functionality
* Allow multiple FPM services to be run in parallel
* Multiple FPM pools per FPM service, listening on per project nginx sockets
* Correct Log and Config paths to be in Boxen locations

## 0.0.1 ##

* Install PHPenv
* Use php-build to install PHP versions
* Install multiple versions of PHP side by side