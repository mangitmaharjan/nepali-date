# Nepali Date

[![Latest Version](https://img.shields.io/github/release/thephpleague/skeleton.svg?style=flat-square)](https://github.com/mangitmaharjan/nepali-date/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Quality Score](https://img.shields.io/scrutinizer/g/thephpleague/skeleton.svg?style=flat-square)](https://packagist.org/packages/makka/nepali_date)
[![Total Downloads](https://img.shields.io/packagist/dt/league/skeleton.svg?style=flat-square)](https://packagist.org/packages/makka/nepali_date)


This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Install

Via Composer

``` bash
$ composer require makka/nepali_date
```

## Add Facade to config/app.php

``` php
'NDate' => Makka\NepaliDate\NepaliDate::class,
```


## Usage

``` php
NDate::eng_to_nep($yy, $mm, $dd)
NDate::nep_to_eng($yy, $mm, $dd)

```


## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
