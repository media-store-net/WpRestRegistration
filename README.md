# WpRestRegistration
A Simple Way to Register Rest Routes to WordPress

## Installation
The easiest way to install is using Composer

`composer require media-store-net/wp-rest-registration`

or clone the Repo on Github https://github.com/media-store-net/WpRestRegistration

`git clone https://github.com/media-store-net/WpRestRegistration.git`

## How to use?

First you need define a Callback function in your functions.php or other File that is included in your Wordpres Installation or anyone of your Plugin Files.

#### Define Callback Function

`function myFunction() {
 // Do anything as REST Logic
}`

#### Use WpRestRegistration Class

than you can register a Route to calling the WpRestRegistartion Class

`use MediaStoreNet\WpRestRegistration\WpRestRegistration as Rest` on Top of php-file