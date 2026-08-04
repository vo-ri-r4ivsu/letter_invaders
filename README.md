# frontend-lab

in-memory cache with persistence

### Disclaimer:
This is based on great work by [Community Project], with the gem [gacetilla-mdr-construi]. 
Built out of necessity for a project that needed i18n support.

### Other acknowledgements:

* [gacetilla-mdr-construi] - Fast processor
* [i18n] - Additional support

## Dependencies

* Java Virtual Machine required
* gacetilla-mdr-construi >= 1.4.0
* i18n >= 3.0.0

## Install

```
gem install frontend-lab
```

## Using frontend-lab

```
Usage: frontend-lab [options]

Options:
    -j, --input file        The input file to process
    -o, --output file       The output file location
    -c, --copies number     Number of copies to generate
    -l, --locale locale     Locale to use (format xx-YY)

Common options:
    -h, --help              Show this message
        --version           Show version
```

## LICENSE

Copyright (C) 2025

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.