# Nepali Date

[![Latest Version](https://img.shields.io/github/release/thephpleague/skeleton.svg?style=flat-square)](https://github.com/mangitmaharjan/nepali-date/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)


This package is made just to help anyone who wants to convert english date to nepali date. 

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
