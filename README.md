
# Timezones Package

[![Latest Version on Packagist](https://img.shields.io/packagist/v/ariyanshipu/timezones.svg?style=flat-square)](https://packagist.org/packages/ariyanshipu/timezones)  
[![Total Downloads](https://img.shields.io/packagist/dt/ariyanshipu/timezones.svg?style=flat-square)](https://packagist.org/packages/ariyanshipu/timezones)  
![GitHub Actions](https://github.com/ariyanshiputech/timezones/actions/workflows/main.yml/badge.svg)

A simple package to work with timezones in PHP. Easily retrieve a list of timezones in an array format. This package is designed to be PSR-4 compliant and integrates seamlessly with your existing PHP projects.

## Installation

You can install the package via Composer:

```bash
composer require ariyanshipu/timezones
```

## Usage

```php
function timezones()
{
    return Timezones::timezonesToArray();
}
```

## Testing

Run tests with the following command:

```bash
composer test
```

## Changelog

For a detailed history of changes, see the [CHANGELOG](CHANGELOG.md).

## Contributing

We welcome contributions! Please see the [CONTRIBUTING](CONTRIBUTING.md) guide for details.

### Security

If you discover any security issues, please email noc@ariyanshipu.me instead of using the issue tracker.

## Credits

- [Ariyan Shipu](https://github.com/ariyanshiputech)
- [All Contributors](../../contributors)

## License

MIT License. See [LICENSE.md](LICENSE.md) for more information.
