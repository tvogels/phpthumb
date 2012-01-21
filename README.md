PHPThumb for use with Symfony2
==============================

Setup
-----

Add the following lines to your `deps` file:

	[PhpThumb]
	   git=http://github.com/tvogels/phpthumb.git
	   target=phpthumb

And those to `app/`:

```php
$loader->registerPrefixes(array(
    ...
    'PhpThumb_'        => __DIR__.'/../vendor/phpthumb/lib',
```

Usage
-----

```php
$thumb = \PhpThumb_Factory::create(...);
```


Sources
-------

1. [PHP Thumbnailer](http://phpthumb.gxdlabs.com/)
2. [PHP Thumbnailer GitHub Repostory](https://github.com/masterexploder/PHPThumb)