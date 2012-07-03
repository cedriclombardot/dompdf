dompdf
======

A [Zend Framework 2](https://github.com/zendframework/zf2/) library that provides
v0.6.0beta3 of the [DOMPDF](http://code.google.com/p/dompdf/) library.

## Requirements
  - [Zend Framework 2](http://www.github.com/zendframework/zf2)

## Installation
Installation of dompdf uses PHP Composer. For more information about
PHP Composer, please visit the official [PHP Composer site](http://getcomposer.org/).

#### Installation steps

  1. `cd my/project/directory`
  2. create a `composer.json` file with following contents:

     ```json
     {
         "require": {
             "dino/dompdf": "dev-master"
         }
     }
     ```
  3. install PHP Composer via `curl -s http://getcomposer.org/installer | php` (on windows, download
     http://getcomposer.org/installer and execute it with PHP)
  4. run `php composer.phar install`

  5. copy the dompdf_config.*.inc.php.dist files to dompdf_config.*.inc.php to your working directory and follow the [dompdf usage docs](http://code.google.com/p/dompdf/wiki/Usage).