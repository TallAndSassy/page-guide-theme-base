# :package_description
[![License](https://img.shields.io/github/license/:vendor_name/:package_name)](https://github.com/:vendor_name/:package_name/blob/master/LICENSE.md)
[![Latest Version on Packagist](https://img.shields.io/packagist/v/:vendor_name/:package_name.svg?style=flat-square)](https://packagist.org/packages/:vendor_name/:package_name)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/:vendor_name/:package_name/run-tests?label=tests)](https://github.com/:vendor_name/:package_name/actions?query=workflow%3Arun-tests+branch%3Amaster)
[![Coverage Status](https://coveralls.io/repos/github/:vendor_name/:package_name/badge.svg?branch=master)](https://coveralls.io/github/:vendor_name/:package_name?branch=master)

[![Total Downloads](https://img.shields.io/packagist/dt/:vendor_name/:package_name.svg?style=flat-square)](https://packagist.org/packages/:vendor_name/:package_name)

**Note:** Run `./configure-skeleton` to get started, or manually replace  ```:author_name``` ```:author_username``` ```:author_email``` ```:vendor_name``` ```:package_name``` ```:package_description``` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](.github/CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line. You can also run `configure-skeleton.sh` to do this automatically.

This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

## Support us

Please send love

## Installation

You can install the package via composer:

[ ] Make a local table for testing called 'tmp_laravel_package' (per 'phpunit.xml')

```bash
composer require spatie/skeleton
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --provider="Spatie\Skeleton\SkeletonServiceProvider" --tag="migrations"
php artisan migrate
```

You can publish the config file with:
```bash
php artisan vendor:publish --provider="Spatie\Skeleton\SkeletonServiceProvider" --tag="config"
```

You can grok the routes (when .env(local)) by visiting 
    
http://test-spatie.test/grok/Spatie/Skeleton/string
http://test-spatie.test/grok/Spatie/Skeleton/controller

This is the contents of the published config file:

```php
return [
];
```

## Usage

``` php
$skeleton = new Spatie\Skeleton();
echo $skeleton->echoPhrase('Hello, Spatie!');
```

## Testing

``` bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [:author_name](https://github.com/:author_username)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
