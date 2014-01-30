# Toolkit

Modular command line interface toolkit.

## Install

```
npm install cli-toolkit
```

## Test

```
npm test
```

To fetch all the modules and then run the tests:

```
npm run refresh
```

## Modules

### Arguments

> Lightweight yet feature rich argument parser

The [argparse][argparse] module is a lightweight yet extremely capable argument parser consisting of ~100 lines of code.

### Command

> Command execution

The [command][command] module glues [define][define] and [argparse][argparse] adding support for more complex command parsing and execution.

### Define

> Chainable argument builder

The [define][define] module allows you to define your programs commands, options and flags in an intuitive and flexible manner using chained method calls.

### Error

> Unified error handling

The [error][error] module is designed around errors with associated exit status codes, it supports i18n should you need it and integrates seamlessly with [ttycolor][ttycolor].

### Locale

> Utilities for working with LC environment variables

The [locale][locale] module provides some utility functions for inspecting the terminal environment and extracting a locale identifer.

### Color

> Colors that respect the tty 

The [ttycolor][ttycolor] module provides support for ANSI escape sequences whilst ensuring your log files are never cluttered with escape sequences.

### Util

> Utility functions for the toolkit

The [util][util] module provides some common functions shared across modules, typically for manipulating strings.

### Notes

This package does not include any code, it serves as a location to document the modules and as a mechanism for running tests across all the modules.

It is also a convenient way to fetch all the modules if you wish to use them all.

## License

Everything is [MIT](http://en.wikipedia.org/wiki/MIT_License). Read the [license](/LICENSE) if you feel inclined.

[argparse]: https://github.com/freeformsystems/cli-argparse
[command]: https://github.com/freeformsystems/cli-command
[define]: https://github.com/freeformsystems/cli-define
[error]: https://github.com/freeformsystems/cli-error
[locale]: https://github.com/freeformsystems/cli-locale
[ttycolor]: https://github.com/freeformsystems/ttycolor
[util]: https://github.com/freeformsystems/cli-util
