# Stop Words

[![Latest Version](https://img.shields.io/github/release/axisofstevil/stop-words.svg?style=flat-square)](https://github.com/axisofstevil/stop-words/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/axisofstevil/stop-words/master.svg?style=flat-square)](https://travis-ci.org/axisofstevil/stop-words)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/axisofstevil/stop-words.svg?style=flat-square)](https://scrutinizer-ci.com/g/axisofstevil/stop-words/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/axisofstevil/stop-words.svg?style=flat-square)](https://scrutinizer-ci.com/g/axisofstevil/stop-words)
[![Total Downloads](https://img.shields.io/packagist/dt/axisofstevil/stop-words.svg?style=flat-square)](https://packagist.org/packages/axisofstevil/stop-words)

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Install

Via Composer

``` bash
$ composer require axisofstevil/stop-words
```

## Usage

``` php
$filter = new Axisofstevil\StopWords\Filter();
echo $filter->cleanText('A Walk to Remember');
```

## Testing

``` bash
$ phpunit
```

## Contributing

Please see [CONTRIBUTING](https://github.com/axisofstevil/stop-words/blob/master/CONTRIBUTING.md) for details.

## Credits

- [Steven Maguire](https://github.com/stevenmaguire)
- [All Contributors](https://github.com/axisofstevil/stop-words/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
