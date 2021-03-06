# wp-plugin-code

## Introduction

The plugin is parse the JSON response and display an HTML table.


## Requirements
> PHP version 7.4 and higher


## Installation using Git

The easiest way to upload the plugin is to use
[Git](https://git-scm.com/). If you don't have it already installed,
then please install as per the [documentation](https://git-scm.com/downloads).

To upload your plugin into the folder `wp-content/plugins`:

```bash
$  git clone git@github.com:LeikoDmitry/wp-parse-users.git wp-parse-users
```

Or
```
$  git clone https://github.com/LeikoDmitry/wp-parse-users.git wp-parse-users
```

After that you should change directory:

```
$ cd wp-parse-users
```

Then you need update all dependencies via composer. If you don't have it already installed,
then please install as per the [documentation](https://getcomposer.org/doc/00-intro.md).

```
$ composer install --no-dev
```

## QA Tools

The plugin does not come with any QA tooling by default, but does ship with
a configuration for each of:

- [phpcs](https://github.com/squizlabs/php_codesniffer)
- [phpunit](https://phpunit.de)

If you want to add these QA tools, execute the following:

```bash
$ composer install
```

We provide aliases for each of these tools in the Composer configuration:

```bash
# Run CS checks:
$ composer cs-check
# Fix CS errors:
$ composer cs-fix
# Run PHPUnit tests:
$ composer test
```
