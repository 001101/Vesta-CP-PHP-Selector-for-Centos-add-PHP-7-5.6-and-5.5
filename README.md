# Vesta CP PHP Selector for Centos add PHP 7, 5.6 and 5.5.

by skamasle 

http://forum.vestacp.com/viewtopic.php?f=19&t=10854


SK PHP Selector:

- This script using vesta templates.
- This script using remi repo.
- I make this script to help people who whant run Multiple PHP versions on vestacp, is easy to do manually but this script makes it easier even
- Ubuntu PHP selector for vesta ?
-- Coming soon, but you need spend time on compilation of php 15 / 20 minutes for each versión.
- Not SUPPORT NGINX + PHP-FPM

http://mirror.skamasle.com/vestacp/testvestacp.png

# Some problems whit big files on joomla, wordpress, plugins or modules fix -> http://forum.vestacp.com/viewtopic.php?f=19&t=10854&p=43843#p43749


  CHANGELOG
:::::::::::::::

UPDATE 
CODE: SELECT ALL
Beta 0.2.3
- Remove some code and tests.
- Using simlinks for templates.


CODE: SELECT ALL
Beta 0.2.2
- Fix bug on centos 6 paths thanks @tjebbeke  to reporting
-- Now check twice php path on centos 6
- Fix Include Optional on centos  6


CODE: SELECT ALL
Beta 0.2.1
- Working on Centos 6.7 and Centos 7
- Detect PHP version.
- Install php 5.4, php 5.5, php 5.6 and php 7.
- Support if php was upgraded, skip that version.


-- Requirements:
- Centos 6 or centos 7
- Default Vesta CP installed whit remi repo

--------------------------------------------------------------------------------

PHP 5.2 - https://forum.vestacp.com/viewtopic.php?f=19&t=13406
