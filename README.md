# Very short description of the package

[![Latest Version on Packagist](https://img.shields.io/packagist/v/divine/reserved-usernames.svg?style=flat-square)](https://packagist.org/packages/divine/reserved-usernames)
[![Build Status](https://img.shields.io/travis/divine/reserved-usernames/master.svg?style=flat-square)](https://travis-ci.org/divine/reserved-usernames)
[![Quality Score](https://img.shields.io/scrutinizer/g/divine/reserved-usernames.svg?style=flat-square)](https://scrutinizer-ci.com/g/divine/reserved-usernames)
[![Total Downloads](https://img.shields.io/packagist/dt/divine/reserved-usernames.svg?style=flat-square)](https://packagist.org/packages/divine/reserved-usernames)

Common prefixes for "role-based" email addresses that represent a position, job, or group of people in the company rather than an individual. These were sourced from several places.

Forked from https://github.com/mixmaxhq/role-based-email-addresses

## Installation

You can install the package via composer:

```bash
composer require divine/reserved-usernames
```

## Usage

``` php
use Divine/ReservedUsernames;

// Initiate
$ru = new ReservedUsernames();

// Get reserved username list
$list = $ru->get();

// Check reserved username, returns false on fail
$check = $ru->check('account');

```

### Testing

``` bash
composer test
```

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Divine](https://github.com/divine)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
