# gyan-date-holidays
Library to fetch holidays of various countries

## Installation
This project using composer.
```
composer require dofruindia/gyan-date-holidays
```

## Usage
Library to fetch holidays of various countries
```php
<?php

use DateHolidays\Holidays;
$api_key = "xxxx-xxxx-xxxx-xxxx-xxxx";
$holidays = new Holidays('US',$api_key);
echo $holidays->getAllHolidays();
```
