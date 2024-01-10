## Contributing [![PHP Tests](https://github.com/PHPSocialNetwork/ravendb-extension/actions/workflows/php.yml/badge.svg)](https://github.com/PHPSocialNetwork/ravendb-extension/actions/workflows/php.yml)
Merge requests are welcome but will require the tests plus the quality tools to pass:

_(Commands must be run from the repository root)_
### PHPCS, PHPMD, PHPSTAN (Level 6), unit tests:

```bash
composer run-script quality
composer run-script tests

# In case you want to fix the code style automatically: 
composer run-script phpcbf
```

## Support & Security

Support for this extension must be posted to the main [Phpfastcache repository](https://github.com/PHPSocialNetwork/phpfastcache/issues).

## Composer installation:

```php
composer install phpfastcache/ravendb-extension
```

#### ⚠️ This extension requires:
1️ The composer `ravendb/ravendb-php-client` library `5.2` at least.

## Events
This driver is currently not emitting [customs events](https://github.com/PHPSocialNetwork/phpfastcache/blob/master/docs/EVENTS.md):
