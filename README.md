php-simple-html-dom-parser
==========================

Version 1.5.3
Tips: This project is a fork from sunra/php-simple-html-dom-parser.

Adaptation for Composer and PSR-0 of:

A HTML DOM parser written in PHP5+ let you manipulate HTML in a very easy way!
Require PHP 5+.
Supports invalid HTML.
Find tags on an HTML page with selectors just like jQuery.
Extract contents from HTML in a single line.

http://simplehtmldom.sourceforge.net/


Install
-------

 composer.phar
```json
"require": {
    "lysice/php-simple-html-dom-parser": "1.5.*"
    }
```

Usage
-----

```php
use Sunra\PhpSimple\HtmlDomParser;

...
$dom = HtmlDomParser::str_get_html( $str );
or 
$dom = HtmlDomParser::file_get_html( $file_name );

$elems = $dom->find($elem_name);
...

```
