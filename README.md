# PHP Coding Standard

[![Latest Version on Packagist](https://img.shields.io/packagist/v/tightenco/tighten-coding-standard.svg?style=flat-square)](https://packagist.org/packages/tightenco/tighten-coding-standard)
[![Run tests](https://github.com/tighten/tighten-coding-standard/workflows/Run%20tests/badge.svg?branch=main)](https://github.com/tighten/tighten-coding-standard/actions?query=workflow%3A%22Run+tests%22)


A PHP CodeSniffer configuration for the Tighten Coding Standard.

## Installation

You can install the package via composer:

```bash
composer require tightenco/tighten-coding-standard
```

Run `./vendor/bin/phpcs -i` to make sure you see "Tighten" in that list.

## Usage

Add the standard to your local `.phpcs.xml.dist`:

```xml
<?xml version="1.0"?>
<ruleset>
   <file>app</file>
   <file>config</file>
   <file>database</file>
   <file>public</file>
   <file>resources</file>
   <file>routes</file>
   <file>tests</file>

   <rule ref="Tighten"/>
</ruleset>
```

## Testing

```bash
composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email hello@tighten.co instead of using the issue tracker.

## Credits

- [Matt Stauffer](https://github.com/mattstauffer)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
