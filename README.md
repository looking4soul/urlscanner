#Url Scanner

[![Software License][ico-license]](LICENSE.md)

Scan urls and report inaccessible urls.

##Install

Via Composer

```bash
$ composer require looking4soul/urlscanner
```

##Usage

```php
<?php
require 'vendor/autoload.php';

$urls = [
	'http://www.baidu.com',
	'http://www.apple.com',
	'http://www.bad_link.com',
];
$s = new \Looking4soul\UrlScanner\UrlScanner($urls);
print_r($s->getInvalidUrls());
```


##Testing

```bash
$ composer test
```

##Security

If you discover any security related issues, please email x.mail.i@qq.com instead of using the issue tracker.

##Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.


## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.


##Credits

- [looking4soul][link-author]


##License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.



[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square

[link-author]: https://github.com/looking4soul