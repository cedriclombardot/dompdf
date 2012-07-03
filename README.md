dompdf
======

PHP Composer package implementation for the [DOMPDF project](http://code.google.com/p/dompdf/).

From DOMPDF project site:

> dompdf is an HTML to PDF converter. At its heart, dompdf is (mostly) [CSS 2.1](http://www.w3.org/TR/CSS2/) compliant HTML layout and rendering engine written in PHP. It is a style-driven renderer: it will download and read external stylesheets, inline style tags, and the style attributes of individual HTML elements. It also supports most presentational [HTML attributes](http://www.w3.org/TR/html4/index/attributes.html).

## Requirements
  - [PHP 5.3+](http://php.net/)

## Installation
Installation of DOMPDF uses PHP Composer. For more information about PHP Composer, please visit the official [PHP Composer site](http://getcomposer.org/).

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

  5. copy the ``dompdf_config.*.inc.php.dist`` files to ``dompdf_config.*.inc.php`` to your working directory and follow the [dompdf usage docs](http://code.google.com/p/dompdf/wiki/Usage).