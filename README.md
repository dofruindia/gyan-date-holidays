# gyan-date-holidays
Library to fetch holidays of various countries

## Installation
This project using composer.
```
$ composer require dofruindia/gyan-date-holidays
```

## Usage
Library to fetch holidays of various countries
```php
<?php

use DateHolidays\Holidays;

$holidays = new Holidays('US');
echo $holidays->getAllHolidays();
```
