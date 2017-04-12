# Laravel-Modules

[![Latest Version on Packagist](https://img.shields.io/packagist/v/softemp/base.svg?style=flat-square)](https://packagist.org/packages/softemp/base)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/softemp/base/master.svg?style=flat-square)](https://travis-ci.org/softemp/base)
[![Scrutinizer Coverage](https://img.shields.io/scrutinizer/coverage/g/softemp/base.svg?maxAge=86400&style=flat-square)](https://scrutinizer-ci.com/g/softemp/base/?branch=master)
[![SensioLabsInsight](https://img.shields.io/sensiolabs/i/25320a08-8af4-475e-a23e-3321f55bf8d2.svg?style=flat-square)](https://insight.sensiolabs.com/projects/25320a08-8af4-475e-a23e-3321f55bf8d2)
[![Quality Score](https://img.shields.io/scrutinizer/g/softemp/base.svg?style=flat-square)](https://scrutinizer-ci.com/g/softemp/base)
[![Total Downloads](https://img.shields.io/packagist/dt/softemp/base.svg?style=flat-square)](https://packagist.org/packages/softemp/base)


- [Installation](#installation)
- [Configuration](#configuration)

<a name="installation"></a>
## Installation

### Quick

To install through composer, simply run the following command:

``` bash
composer require softemp/base
```

#### Add Service Provider

Next add the following service provider in `config/app.php`.

```php
'providers' => [
  Llama\Modules\ModuleServiceProvider::class,
],
```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.