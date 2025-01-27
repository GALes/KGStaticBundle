KGStaticBundle
==============

[![Build Status](https://img.shields.io/travis/kgilden/KGStaticBundle/master.svg?style=flat)](https://travis-ci.org/kgilden/KGStaticBundle)

This bundle allows you to load static content from files using Symfony's
shorthand "@" syntax.

Usage
-----

```twig
{# in '/some/path/to/template.html.twig' #}

{{ file('@AcmeDemoBundle/Resources/files/hello.txt') }}

```

Installation
------------

Add KGPagerBundle in your `composer.json`:

```json
{
    "require": {
        "kgilden/static-bundle": "~1.0"
    }
}
```

Directamente con composer

```
composer require kgilden/static-bundle
```
Register the bundle in app/AppKernel.php:

```php
new KG\StaticBundle\KGStaticBUndle(),
```

Tests
-----

Simply run `phpunit` in the root directory for the full test suite.

Licence
-------

This bundle is under the MIT license. See the complete license in the bundle:

    Resources/meta/LICENCE
