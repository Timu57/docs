<!--METADATA
{
    "title": "Installation",
    "url": "Installation",
    "icon": "play"
}
!METADATA-->

# Installation

To use SleekDB make sure that you have PHP up and running in your system, and SleekDB has write permission.

## Using SleekDB in a PHP project

### Composer Installation (recommended)

To install SleekDB using composer, open a terminal, cd into your project root directory where "composer.json" file lives and run this:

```sh
composer require rakibtg/sleekdb
```

SleekDB should be auto loaded into your app using the composer.
Find SleekDB on **<a href="https://packagist.org/packages/rakibtg/sleekdb" target="_blank">packagist</a>**.

### Install Manually (without composer)

- <a href=" https://github.com/rakibtg/SleekDB/archive/master.zip">Download</a> the latest version and extract the ZIP file inside your project directory.
- Import the SleekDB.php file where you want to use SleekDB.

  Example:

  ```php
  require_once "../SleekDB/SleekDB.php";
  ```

To download older versions please check the <a target="_blank" title="Click here to download old versions" href="https://github.com/rakibtg/SleekDB/releases">releases</a>.
