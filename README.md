# Laravel Bootstrap Components

[![Latest Version on Packagist](https://img.shields.io/packagist/v/appstract/laravel-bootstrap-components.svg?style=flat-square)](https://packagist.org/packages/appstract/laravel-bootstrap-components)
[![Total Downloads](https://img.shields.io/packagist/dt/appstract/laravel-bootstrap-components.svg?style=flat-square)](https://packagist.org/packages/appstract/laravel-bootstrap-components)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/appstract/laravel-bootstrap-components/master.svg?style=flat-square)](https://travis-ci.org/appstract/laravel-bootstrap-components)

Easily use bootstrap components as Laravel components. Requires Laravel 5.4+

At this moment only Bootstrap 4 is supported. The package is in constant development and new components will be added regulary. You can help with adding components by creating a pull request.

## Installation

You can install the package via composer:

```bash
composer require appstract/laravel-bootstrap-components
```

### Provider

Then add the ServiceProvider to your `config/app.php` file:

```php
'providers' => [
    ...

    Appstract\BootstrapComponents\BootstrapComponentsServiceProvider::class

    ....
]
```

## Usage

```blade
@component('bootstrap::modal')
    This is the content of the modal
@endcomponent
```

Check the [wiki](https://github.com/appstract/laravel-bootstrap-components/wiki) for more documentation.


## Contributing

Contributions are very welcome! If you want to add a component, please keep the following in mind when creating a pull request:

- Have a look at the existing components for examples
- Customization of the component (like custom classes and options for the component)
- We higly appreciate if you can add support for multiple Bootstrap versions, but it is not required
- Provide some docs in the Wiki

[Thanks to all the contributors](https://github.com/appstract/laravel-bootstrap-components/graphs/contributors)

## About Appstract

Appstract is a small team from The Netherlands. We create (open source) tools for webdevelopment and write about related subjects on [Medium](https://medium.com/appstract). You can [follow us on Twitter](https://twitter.com/teamappstract), [buy us a beer](https://www.paypal.me/teamappstract/10) or [support us on Patreon](https://www.patreon.com/appstract).

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
