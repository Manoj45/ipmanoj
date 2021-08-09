visitorTracking [![GitHub License](https://img.shields.io/github/license/theshka/visitorTracking.svg)](https://github.com/theshka/visitorTracking/blob/master/LICENSE.md) [![GitHub Release](https://img.shields.io/github/release/theshka/visitorTracking.svg)](https://github.com/theshka/visitorTracking/releases/latest)
======

**visitorTracking** is a simple PHP class to gather visitor information, and store it in a database using MYSQLi. It's more modern and complete than others I have seen around on Google/HotScripts. (SQLi, oop(ish?), etc...) No bells or whistles, fully customizable.

## Download
* [Dev-Master](https://github.com/theshka/visitorTracking/archive/master.zip)
* [Version 1.2.1](https://github.com/theshka/visitorTracking/archive/v.1.2.1.zip)

### Old Versions
* [Version 0.0.1](https://github.com/theshka/visitorTracking/archive/v0.1.zip)

## Documentation
[http://tyrexi.us/visitorTrackingDocumentation](http://tyrexi.us/visitorTrackingDocumentation)

## Demo
[http://tyrexi.us/visitorTracking](http://tyrexi.us/visitorTracking)

## Install
1. Upload the files to your server.

1. Edit the database configuration ( `src/_installation/db.php` )

1. Create the `visitors` table in your database. (`src/_installation/visitors.sql` )

1. Instance the class in your code.

## Usage
```php
//define database
define( 'DB_HOST', 'localhost' );           // set database host
define( 'DB_USER', 'root' );                // set database user
define( 'DB_PASS', '' );                    // set database password
define( 'DB_NAME', 'yourdatabasename' );    // set database name

//include the class
include( 'src/class.visitorTracking.php' );

//instance the class
$visitors = new visitorTracking();
```
