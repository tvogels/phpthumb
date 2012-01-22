PhpThumb for use with Symfony2
==============================

Setup
-----

Add the following lines to your `deps` file:

	[PhpThumb]
	   git=http://github.com/tvogels/phpthumb.git
	   target=phpthumb

And those to `app/autoload.php`:

```php
$loader->registerPrefixes(array(
    ...
    'PhpThumb_'        => __DIR__.'/../vendor/phpthumb/lib',
```

Now run `php bin/vendors update` or `php bin/vendors install`.

Usage
-----

```php
$thumb = \PhpThumb_Factory::create(...);
```


Sources
-------

1. [PHP Thumbnailer](http://phpthumb.gxdlabs.com/)
2. [PHP Thumbnailer GitHub Repostory](https://github.com/masterexploder/PHPThumb)